# pngnumberer
This bash script works on a PNG image, adding a text rectangle onto it
and writing that out to another PNG image.

Intended use is common car liveries customization.

It requires ppmlabel, pnmtopng and pngtopnm from the netpbm package.

Usage: pngnumberer [OPTION]... [FILE]...
-x value 
-y value 
-n NUM 
filename

In addition to the mandatory arguments, you may specify
-r for 180 degrees rotation.

A rectangle will be drawn at the position given
and depicting NUM to an image FILE. 
A new file will be created by prepending NUM to the name.
Neither existing file will be modified.
The coordinates are for the bottom left corner of this rectangle.

