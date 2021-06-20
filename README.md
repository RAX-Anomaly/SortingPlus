# SortingPlus
Reenables categorized grouping of items in the inventory screens.
Optional AMCM support allows for selecting which screens. 

I say reenable because Tronex built this system in ui_inventory and then commented out the lines that would have enabled it. I just set those flags.

SortingPlus now adds aditional orginal features providing sorting control beyound that available in the built in code.

sortingplus.ltx now controls the sorting order and groups when not using AMCM or when "Use sortingplus.ltx" is selected in AMCM. AMCM also has less granular in game method for adjusting sorting order and groups. (35 categories in ltx combined down to 15 in AMCM menu)

Hovering the mouse over an item and pressing the K key will cause it to be added to a list of favorited items. Favorited items can be prevented from transferring when the Put all Button is used.

Hovering the mouse over an item and pressing the J key will cause it to be added to a list of junk items. Junk items can be set to automatically move to the selling window of traders that will buy them.

Items in these list are treated as if in a category together. that category's position in the list can be adjusted just like the other categories via AMCM or the LTX. Defaults to the top of the list for favorites, bottom for junk. Color highlighting no longer requires another mod.

Favorites/Junk are stored by section. What this means is that an AN-94 is not the same as an AN-94 with a scope on it. If you add attachments you will need to re-favorite your gun, but only once for each configuration.

sortingplus.ltx now has a section offering item by item kind override. This can be used to move an item from one catagory to another when you don't agree with the orginal classification.
