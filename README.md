TabGroupJumper
==============

Add-in exposing keyboard shortcuts for jumping between left/right tabgroups


This addon was pretty sweet when used with VSVim, but it didn't work in more recent VS versions due to the versioning system.
This was an easy fix, but it may not be intuitive to people who haven't worked with VS addons before.

To get it working put:

TabGroupJumper.AddIn

TabGroupJumper.dll (in bin)

and

TabGroupJumper.XML (in bin)




In a folder, then in VS go to Tools->Options->Environment->Add-In->Add-in Security.

Then just add the folder and restart visual studio.
