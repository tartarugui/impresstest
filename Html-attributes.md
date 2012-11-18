# Attributes API
This is a summary of the available attributes. Every effort will be made to keep it up to date. However, the project (as usual) evolves faster than the documentation. Refer to the code for details if you encounter trouble following this advice:



# SYSTEMIC ATTRIBUTES
Apply these to your ```#impress``` element.

## Animation Speed
### data-transition-duration
Specified in milliseconds. Effects all impress functions/transitions. May one day be applicable to [individual steps](https://github.com/bartaz/impress.js/issues/142), but for now only exists globally.



# STEP FRAME ATTRIBUTES
## Cartesian Position
Where in 3D space to position the step frame in Cartesian space.

### data-x, data-y, data-z
Define the origin location in 3D Cartesian space. Specified in pixels (sort-of).

### data-rotate
Rotation of the step frame about its origin in the X-Y plane. This is akin to rotating a piece of paper in front of your face while maintaining it's ortho-normality to your image plane (did that explanation help? I didn't think so...). It rotates the way a photo viewer rotates, like when changing from portrait to landscape view.

## Polar Position
Rotation of the step frame about its origin along the theta (azimuth) and phi (elevation) axes. This effect is similar to tilting the frame away from you (elevation) or imaging it standing on a turntable -- and then rotating the turntable (azimuth).

### data-rotate-x
Rotation along the theta (azimuth) axis

### data-rotate-y
Rotation along the phi (elevation) axis

## Size

### data-scale
The multiple of the "normal" size of the step frame. Has no absolute visual impact, but works to create relative size differences between frames. Effectively, it is controlling how "close" the camera is placed relative to the step frame.