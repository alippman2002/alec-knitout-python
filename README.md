# alec-knitout
Alec's knitout files for Bertoldi Group (Python and Knitout)

Developing variations of a specific fold structure in knits can quickly become a tedious process using current 3D knitting softwares. To address this challenge, a piece of software which automates the placement of low-level knit operations is created to streamline the iterative development process of manufactured pleats. This software tool will reduce the R&D phase of wearable development which utilize knitted folds. One wearable application is adaptive insulation or wearables that require variable surface area. This project explores the application of this software through developing the square waterbomb tessellation fold in a knit swatch. The project is developed using Knitout, a knitting programming language where its output is compatible with various knitting machines.

The python files use pixel-logic to encode specific knit operations based on the RBG value of the pixel. Working with a pixel file as an input can rapidly streamline the development and analyis of knits and their mechanics.

Simple knit programs which generate a .k Knitout file are found in initial_dev folder. Pixel-based development for the square waterbomb tessellation fold are in the pixel folder. Pixel inputs used to debug and to create varying origami knits are found in pixel/pixel_ref. The .k files generated for each tessellation knit can also be referenced.

To use pixel.py, create a pixel input using white, red, and black:

White -> Mountain Fold
Black -> Flat Section
Red -> Valley Fold

Add your pixel file's name into pixel.py and a .k file will be written when the program is run. The .k file can be written to instructions for a Shima or Kniterate industrial machine.
