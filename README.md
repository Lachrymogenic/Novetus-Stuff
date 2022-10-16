# Rose Pink Theme
An example theme for NovetusFE to serve as a rose pink theme and an example on how to create themes for NovetusFE.
# Theme Documentation
## index.json
index.json is a property setter file with special functions included, such as Vector2() and image(), inside of index.json, you can select nodes and then set their properties, such as their position, their size, and anything else. To use index.json, I highly recommend that you open the project inside of Godot to get familiar with the Scene Tree, but for a brief rundown, here are the main nodes:

- Background
- Controls
- Main
- OverlayLayer

Path to nodes is directed by slashes.

## The .tres files
The names of the .tres files are self explanatory, panel.tres changes all panels, and button-normal changes the look of buttons etc etc. For information on how to style these, what properties you can use, read the top of the .tres file, panel.tres shows "gd_resource type="StyleBoxFlat" format=2" so look up StyleBoxFlat on the Godot Documentations to check which properties you can change. A link for styleboxflat is here: https://docs.godotengine.org/en/stable/classes/class_styleboxflat.html

## Custom images
Custom images will only work on texture nodes, an example of how to set one is in this themes ``index.json``. Use ``image(filename.png, sizex, sizey)`` . Your custom images must be included with your theme, downloading from the internet is not supported.
