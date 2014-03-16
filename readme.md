# Alfred Workflow for `doing`

Please read the [project page for `doing` by Brett Terpstra](http://brettterpstra.com/projects/doing/). He's a LaunchBar user and suggested that someone could whip up an Alfred Workflow, so I did. This is a straight port of his LaunchBar script that allows either the simple adding of a new item or asking what are the recent items. Much more is available via the CLI, and could be added later, but let's start with this.

## How to use

1. Follow [his instructions](http://brettterpstra.com/projects/doing/) (tl;dr: `gem install doing`)
2. [Install this Workflow](https://github.com/EvanLovely/alfred--doing/raw/master/Doing.alfredworkflow)
3. Type `doing ?` to get a Large Type display of your recent items. Identical to running `doing recent`. Hold Command to get the list from the Later list. Identitcal to running `doing show later`.
4. Type `doing "new item to do"` to add "new item to do" to your current list. Identical to running `doing now "new item to do"`. Hold Command to send it to the Later List, identical to running `doing later "item to do"`.

### How to make sure Alfred's query window is dismissed after running `doing ?`

After you run `doing ?`, you may notice Alfred's window is still hanging around, to fix that change this:

![Turn on Auto-Hide Large Type in Alfred Prefs](https://github.com/EvanLovely/alfred--doing/raw/master/assets/alfred-large-type.png)

Hat tip to [Sam Kimbrel](http://www.samkimbrel.com/posts/2013-12-24-os-x-shell-large-type.html) for that, along with the way to get Alfred's Large Type to be scriptable. 