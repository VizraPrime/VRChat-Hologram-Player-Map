# Vizra's Hologram Player Location Map
I noticed that there isn't any prefab online for the kind of hologram map used in a lot of game worlds. So I wanted to help people out and make this public!

# Features
-Shows player position
-Shows player usernames
-Allows clicking on player icons to teleport to them.
-Late join compatible with minimal networking, (Doesn't use ownership.)

# Prerequisites
TextMeshPro

# Instalation
-Drag and Drop into the scene

-Zero the tranaform compoent (Position 0,0,0, rotation 0,0,0, scale 1,1,1.) 

-Delete/match up squares/cubes to match the layout of your world, once finished you can move rotate and acale the prefab to whatever you need. Rotations for nameplates are automatic.

-Edit the font or Size of the text mesh component as you wish.

# Variables
-UpdateRate: Change how fast the locations are updated in Frames. Higher numbers are slower.

-PlayerTrackers: You can duplucate trackers and add them to the gameobject array as needed.

-ResetLocation: This will be the position where objects return to when not in use. It will be scaled down along with the prefab so you may need to use numbers in the 100's



I hope it helps people make some cool meals!
