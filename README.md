# Project 1 - Ray casting
# Graham Efthymiou
# gefthym

Newly added functionality:
 - Ray class
 - Vector class
   - new functions: multiply, divide, mag all to simplify calculations


 - Light class
 > function: **drawColoredEllipsoids**: renders ellipsoids on screen and shades them if a light source is given
 > Parameters:
**context**: context of the html canvas
**eye**: vector location of the eye
**light (optional)**: light class passed in which has vectors for location, ambient, diffuse, and specular light. If this param is left out, no illumination will be done

 > function: **blinnPhong**: calculates the rgb color value of a point found using the t value and ray equation, on an ellipsoid given a light source
 > Parameters:
 **context**: context of the html canvas
**eye**: vector location of the eye
**light**: light class passed in which has vectors for location, ambient, diffuse, and specular light.


