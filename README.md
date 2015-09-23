# Snap.js

Added permanently visible shelf stripe to Snap.js via the added shelfAlwaysVisibleThreshold parameter. 

Forked from: https://github.com/jakiestfu/Snap.js

Always use the shelfAlwaysVisibleThreshold parameter in conjunction with the maxPosition / minPosition (depending on if your menu shelf is on the left or right side), setting for example
minPosition: 70 and shelfAlwaysVisibleThreshold: 70 to create an always visible shelf stripe to the left of the screen, when the menu is normally gone in its closed state. 