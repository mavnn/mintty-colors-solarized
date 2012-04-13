# Color settings for the Cygwin mintty terminal

Based on the solarized color scheme by Ethan Schoonover. See full details at http://ethanschoonover.com/solarized

This project can be found at
https://github.com/mavnn/mintty-colors-solarized and is designed to be included as a subtree of https://github.com/altercation/solarized

## Adding to your login scripts

Copy the two files into a directory in your home (for example .solar) and add one of the following lines to your .bashrc file:

	source ~/%your directory%/sol.light
or

	source ~/%your directory%/sol.dark

Color schemes can be swapped interactively using the same commands.

## Mintty internal defaults

You can also set these as the default in your ~/.mintty configuration file.  This means that a mintty terminal reset doesnt loose your color settings. Simply append the appropriate file to your mintty config file (~/.mintty) and then edit the file and tweak as below:

	cat ./.mintty.light >> ~/.mintty
or

	cat ./.mintty.dark >> ~/.mintty

Then open the config file and remove the 3 pre-existing color settings for:

	ForegroundColour= ...
	BackgroundColour= ...
	CursorColour= ...

as they will be re-specified further down in the appended section.
