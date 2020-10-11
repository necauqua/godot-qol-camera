# QoL Camera
This is a simple (at the moment) plugin, which adds some essential quality of life features to the Godot's Camera node.

At this moment it has only one such feature - the 'Lock to view' inspector toggle, which makes the camera follow the position and rotation of the editor camera such that it would produce the image from the same angle as you see it from the viewport. Also it temporarily synchronizes editor camera settings with the locked camera, so you will preview how the FOV and other settings would look like.

## Installation
Copy the `addons/qol-camera` folder into `res://addons/` folder of your project (creating one if you don't have one, obviously).

Then in the `Project`->`Project Settings` in the `Plugins` tab enable (by toggling the checkbox) the `QoL Camera` plugin, which should appear there.
