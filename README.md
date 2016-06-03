# SvgtoGcode

Processing sketch to convert your Svg files to Gcode ready for CNC Drawing machines.

##How to use this sketch
To use this sketch you need the processing library :
https://github.com/rikrd/geomerative

Because CNC machines have different settings you can set up your output Gcode:

**fileName**   -> File you will convert, it has to be placed in the same directory
**penUp**  / **penDown** -> Gcode command to lift your pen
**xcoord** / **ycoord** -> Minimum and maximum value for each axis
