# QTCCV Reborn
Based off the original by Axisok, this attempts to add more features like color


## Requirements
### For decoding
It's already included
 - [wave](https://github.com/CrazedProgrammer/wave)

### For encoding
You can install those with pip.
 - numpy
 - moviepy

## How to use
Use `py encoder.py -c quadtree -i <video file> -o <output file>` to convert a file, then get that file on a computer with the video player and run `videoplayer <qtv file>`. The file must have a .qtv extension, and the name given to the Lua program must not include it. It's done this way because to play audio it simply reads a .nbs file with the same name. Not optimal, but I wanted to have something that worked quickly, so some sacrifices had to be made.

## Credits
Most was created by Axisok
