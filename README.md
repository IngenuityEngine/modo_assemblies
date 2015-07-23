# MODO Assemblies
Various modo assemblies we've built at [Ingenuity](http://ingenuitystudios.com)

## Installation
1. Click Download ZIP to the right
2. In MODO click System > Open Content Folder
3. From there browse to Assets > Assemblies
4. Extract fitFloat.lxp and joystick.lxp to this folder
5. Hit F6 to open the presets dialog
6. Both presets should be under assemblies

## fitFloat
Fits a float parameter to a given range.  Similar to the fit node in Houdini or Rescale in Softimage.  Check out joystickAndFixFloat.lxo in example scenes.

Use:

1. Hit F6 to open the presets dialog
2. Navigate to Assemblies
3. Drag fitFloat in to the schematic
4. Remap params!

## joystick
A simple joystick for rigging.  It has box, horizontal, and vertical  modes with a constrained puck for animation.  The horizontal and vertical values are output for linking in Schematic View.  Most of the params are in the User Channels.  The label and color can be changed under Display.  Check out joystickAndFixFloat.lxo in example scenes.

Use:

1. Hit F6 to open the presets dialog
2. Navigate to Assemblies
3. Drag joystick into a 3D viewport
4. Select the frame then select User Channels
5. Drag horizontalValue and verticalValue into the schematic view
6. Connect them to things!

#####Params (located on the frame):
__joystickType__

	box, horizontal, vertical

__joystickSize__

	size of the frame and puck

__joystickOvercrank__

	how far outside the box the puck can go

__horizontalValue__

	0-1 from left to right

__verticalValue__

	0-1 from bottom to top

