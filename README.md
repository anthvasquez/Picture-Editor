# Picture-Editor
A basic picture editor written using javaFX.

File format:

Line 1: one value, picture name
Line 2: two values, number of grid rows, number of grid columns
Line 3: four values, background color components — red, green, blue, opacity — as percentages (0.0-100.0)
Remaining lines: six values, inidividual light (grid cell) description — row index, column index, red, green, blue, opacity


An example file is included. Please use this file as a starting point; there is no error checking for incompatible files.


Known bugs:
Using custom colors that have an opacity of less than 100% are sometimes drawn more opaque than intended.  This is can be reset by changing to erase mode and clicking anywhere on the canvas

The cursor for paint mode and erase mode do not work on OSX operating systems.
