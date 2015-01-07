To install, "Download Zip" to the right, and double click the .sketchplugin file.

### Name Artboards and Draw Slice
Goes through each artboard and creates a text label where the artboard name sits so it is visible when exporting with slices. It also draws a slice around all visible content (toggleable).
![Dialog prompt](http://cl.ly/image/1v0z3L1l2P2e/Image%202015-01-07%20at%203.43.50%20PM.png)
![Artboard labels group with slice](http://cl.ly/image/3t1R0i2M030e/Image%202015-01-07%20at%203.44.50%20PM.png)

If you move / change artboard names, just re-run the plugin and it will replace the old 'Artboard labels' group with a new one! Careful not to have other groups with the same name — it will be erased.

# Changelog
*v1.2.1*
- Fixes a logic error that could cause slices to be drawn incorrectly if artboards are in a particular order.

*v1.2*
- Now also draws a slice around all visible layers/artboards named 'Slice'. There's a checkbox in the prompt that allows you to toggle this.
