# TypeFaces

TypeFaces is an ASCII art generator powered by Haskell. Haskell handles large amounts of data and recursion very well. This program takes advantage of that. It's very fast!


## Usage instructions

In the folder where you extracted typefaces.exe and the BMP image files, open typefaces.exe.
You can do this by double-clicking on the file.

You'll be prompted to entire a filename. This must be a BMP image in the same folder.
For example, try one of:

	jojo.bmp
	cuhacking small.bmp
	stallman.bmp
	
You'll then be prompted whether you have a dark terminal.
Enter "y" if your command line has bright text on a dark background, like black.
Enter "n" if your command line's background is white. This will invert the shades used.

Lastly, you'll be prompted to enter a string of symbols.
Put the characters that you would like to represent darker pixels first, and 
characters that would represent brighter pixels last.

Try one of the following palette strings (without quotes):

	"-O"
	" .^OW"
	" ./^QWZZ"
	"$@B%8&WM#*oahkbdpqwmZO0QLCJUYXzcvunxrjft/|()1{}[]?-_+~<>i!lI;:,^ "
	
For example, " .^OW" means that the darkest pixels will be represented by a space (" "), 
and the four other characters will be used to represent four other shades, up to brightest 
shades in the given image that will be represented by "W".
Answering "n" to having a dark terminal will effectively treat the palette string as 
the reverse: "WO^. ".
	
Then, the image will be displayed in the command line.
Larger images will probably appear quite zoomed in.
Reduce the font size of your terminal emulator, zoom out, or increase the window size 
to see the full details of the art. Otherwise, just scroll.

The program will keep prompting you for another image to convert to ASCII art until you 
close the program. Experiment with other BMP images and other palette strings!
