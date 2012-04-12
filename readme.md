# Color settings for the Cygwin mintty terminal

Based on the solarized color scheme by Ethan Schoonover. See full
details at http://ethanschoonover.com/solarized

This project can be found at
https://github.com/mavnn/mintty-colors-solarized and is designed to be
included as a subtree of https://github.com/altercation/solarized

Copy the two files into a directory in your home (for example .solar) 
and add one of the following lines to your .bashrc file:

source ~/%your directory%/sol.light

or

source ~/%your directory%/sol.dark

Color schemes can be swapped interactively using the same commands.

You can also set these deafults in your ~/.mintty configuration file.  
This means that resets etc. dont loose your color settings. 
Add the appropriate sections (without the comment lines):


# Dark
ForegroundColour=131, 148, 150
BackgroundColour=  0,  43,  54

# Light
ForegroundColour=101, 123, 131
BackgroundColour=253, 246, 227

# Common
CursorColour=    220,  50,  47
Black=             7,  54,  66
BoldBlack=         0,  43,  54
Red=             220,  50,  47
BoldRed=         203,  75,  22
Green=           133, 153,   0
BoldGreen=        88, 110, 117
Yellow=          181, 137,   0
BoldYellow=      101, 123, 131
Blue=             38, 139, 210
BoldBlue=        131, 148, 150
Magenta=         211,  54, 130
BoldMagenta=     108, 113, 196
Cyan=             42, 161, 152
BoldCyan=        147, 161, 161
White=           238, 232, 213
BoldWhite=       253, 246, 227
