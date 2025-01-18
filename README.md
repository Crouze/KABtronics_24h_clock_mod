# KABtronics 24-hour clock
Add-on board to turn the KABtronics Transistor Clock into an 24-hour clock.

Please read [this blog post](https://blog.crouze.com/transistor-clock/) first, it explains what I did, and why. Then continue here if you are interested in building your own modification board.

First step is of course to order a PCB from your preferred source. The Gerber files for version 1.1 are in this repository. These have all the errors I made with the original daughter board (as shown on the images here) corrected. 

Components needed are all similar to those used on the main board: NPN transistors (2N3904), diodes (1N4148) and resistors (10k, 100k and 680r). You will need more of those than what is left over from not needing these on the main board.

Wiring on the daughter board speak for themselves and are clear enough in the images on the blog post. As mentioned there the two top blue wires are not needed.

For convenience I have numbered the connections needed between the man board and the 24-hour daughter board. It is up to you how you make those connections, hard wired or with soke form of male/female connectors. Although they look good I do not recommend the connectors I made with a 3D printer, so I will not share these .

The connections are numbered in these two images of the bottom of the 24-hour daughter board. Please disregard the pin in the first image, and the two bridge wires in the second. These are for a LED (irrelevant here) and to correct a mistake made with the original board.

![](/images/24h_board_bottom_1.jpg)
![](/images/24h_board_bottom_2.jpg)

The first four connections are show here, on the bottom of the main board. Do not forget the eight rate control capacitors (220pF), they are really necessary. Some are hidden here under the connectors but their locations should be obvious:

![](/images/main_board_bottom_1.jpg)

Connections to be made directly the right-most 7-segment LED as shown here on the bottom of the main board:

![](/images/main_board_bottom_2.jpg)

And finally all the other connections (22 and 24 are the same as in the previous image):

![](/images/main_board_top.jpg)

Good luck! And I would much appreciate it if you can share your succesful implementation (preferably via [my blog](https://blog.crouze.com/transistor-clock/)).

NOTE: I do not take any responsibility, nor will I support when the modification does not work.
