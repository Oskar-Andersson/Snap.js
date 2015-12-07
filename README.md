# Snap.js

Rewrote original snap (a mobile swipe side menu plugin) to be a static left menu always visible shelf menu for desktop web. Use width parameter to set shelf width. Removed dragging events since we do not use this. Added responsivitiy to resize.

- Only tested with shelf on left side, will need work to tackle right side 
- Needs more work on setting the shelf width. Currently, shelf extends 100% of the width of the screen behind content, maiking "float: right" unviable style for anything in the left shelf. Hope to fix this in the future.