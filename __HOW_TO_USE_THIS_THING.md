## How to use this prose.io thing.

You probably want to edit a tab. In that case, click on the folder that says "tabs", and you will see a bunch of files that end in .md. Each of these files corresponds to a tab. Click on them to edit it.

When you are done making changes, click on the "save" icon to the right. Then email richard.marmorstein@gmail.com to tell him to publish the changes.

### How to make a new tab.
Click 'create a new file'. Then, at the top of the file put something like

```
---
title: TITLE
position: 50
in_tab_list: true
---
```
(do not include the backticks, but do include the hyphens)

* The value for "title" will be the label that goes on the tab.
* The "position" will determine where the tab occurs on the list of tabs. Tabs with smaller values come first in the list.
* Put `in_tab_list: false` if you do not want it actually to appear in the tab list---if it should be hidden, and only
accessible by being linked to from other tabs.

Below that, put the content of the tab.

### How to delete a tab.

Click on that tab's file, click on the gear wheel to the right, and then click "delete file."

### How to
