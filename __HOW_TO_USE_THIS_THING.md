## How to use this prose.io thing.

### Editing a tab
Click on the folder that says `_tabs.`
This will open a folder. Every file in this folder is a tab.
The files are in a special format called markdown---the editor will help you with this.

## Saving your changes
When you are done making changes, click on the "save" icon to the right. Then click "commit".

Probably, it won't work the first time you try. On the bottom right corner, there will be a little green icon about "authorizing github". Click it.

This will take you to github.com. You will need to create an account. Create it. Then the save button should work.

After you save your change, email richard.marmorstein@gmail.com to tell him to publish the changes.


### How to make a new tab.
Click 'create a new file'. Then, at the top of the file put something like

---
title: My New Tab
position: 50
in_tab_list: true
---
Hello this is my new tab.
This is stuff I am writing in my new tab.
New tabs are the greatest thing.
Ok I am done with the tab.

* Up above the editor, make sure to make the filename something sensible that ends in .md
* For example `mynewtab.md`
* Make sure to include the hyphens '---'
* "title" will be the label that goes on the tab.
* "position" will determine where the tab occurs on the list of tabs. Tabs with smaller values come first in the list.
* "in_tab_list" true will ensure it appears on the list of tabs. 
* "in_tab_list: false" will cause it to be omitted from the tab list---but you can still link to the page from another tab.

### How to delete a tab.

Click on that tab's file, click on the gear wheel to the right, and then click "delete file."

### How to link to a tab

For example, do [here is the text of the link](/anothertab) will link to the tab in the file "anothertab.md". Links are based off the filename. Make sure to include the initial slash.
