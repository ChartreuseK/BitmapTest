BitmapTest
==========

Test of creating a bitmap image in C

This project creates a BITMAPCOREHEADER format BMP file using C, in it's current form it uses packed headers and as such is not portable to big-endian architectures, or ones which require specific alignment for accessing variables (eg SPARC).

The current demo creates a 128x84 1bpp bitmap displaying an 8x8 font I designed for my NTSC Serial Terminal project.

![Example Output](https://raw.githubusercontent.com/ChartreuseK/BitmapTest/master/test.bmp)
