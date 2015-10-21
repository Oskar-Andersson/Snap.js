# Snap.js

Added permanently visible shelf stripe to Snap.js via the added shelfAlwaysVisibleThreshold parameter. 

Removed dragging events since we do not use this. 

Added responsivitiy to resize etc. 

- Only tested with shelf on left side.
- Always use the shelfAlwaysVisibleThreshold parameter in conjunction with the maxPosition / minPosition (depending on if your menu shelf is on the left or right side), setting for example
minPosition: 70 and shelfAlwaysVisibleThreshold: 70 to create an always visible shelf stripe to the left of the screen, when the menu is normally gone in its closed state. 