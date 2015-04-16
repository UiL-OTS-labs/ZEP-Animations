# Animation Sniplet

This is a test sandbox for CSV based animation of ImageShapes of ZEP. Tested in 1.10

This entails that you define the movements to be made relative to the current situation (at the start of the animation). You do this in an csv. Examples of animations can be found in:
 stimuli/animations/

Note that everything is defined relative. For instance, setting x to 10px will INCREASE the x with 10px. Defining it as 0px or 0% equals the values at the start of the animation. That way, returning to the start position can be done by setting everything to 0.

# Member Details

Some of the variables (i.e. x, y, width, height) can be defined in percentage.

The *rotation* is clockwise and in radials (i.e. 2pi equals one full rotation).

The *y axis* is orientated to be positive towards the bottom. That is, the [0;0] point is in the top left and [0;10] is 10px lower. 

# Bugs

Changing height or width while in a rotation influences the picture.
