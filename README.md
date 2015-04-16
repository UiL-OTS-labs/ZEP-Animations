# Animation sniplet

This is a test sandbox for CSV based animation of ImageShapes of ZEP. Tested in 1.10

This entails that you define the movements to be made relative to the current situation (at the start of the animation). You do this in an csv. Examples of animations can be found in:
 stimuli/animations/

Note that everything is defined relative. For instance, setting x to 10px will INCREASE the x with 10px. Defining it as 0px or 0% equals the values at the start of the animation. That way, returning to the start position can be done by setting everything to 0.

# Member Types

Some of the variables (i.e. x, y, width, height) can be defined in percentage.
Note that the rotation is clockwise and in radials (i.e. 2pi equals one full rotation).

# Bugs

Changing height or width while in a rotation influences the picture.
