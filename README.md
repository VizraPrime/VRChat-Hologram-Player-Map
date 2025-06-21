# Vizra's Hologram Player Location Map
I noticed that there isn't any prefab online for the kind of hologram map used in a lot of game worlds. So I wanted to help people out and make this public!

# Prerequisites
TextMeshPro, that should be it.

# Instalation
-Drag and Drop, Move the _"Holomap"_ prefab where you need it.

-Move the _"HolomapUI"_ where you need it.

-Customize the layout by scaling up _"Holomap-Interior-Rooms"_ to **1**, delete/match up squares/cubes to match the layout of your world, then scale the prefab root down to whatever size you need. Rotations should be automatic.

# Variables
-Update rate: Change how fast the locations are updated in Frames. Higher numbers are slower.

-Amount of Trackers: You can duplucate trackers and add them to the gameobject array as needed.

-Reset Position: This will be the position where objects return to when not in use. It will be scaled down along with the prefab so you may need to use numbers in the 100's
