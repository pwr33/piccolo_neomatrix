piccolo_neomatrix
=================

Adafruit spectrum visualiser working on an 8x8 neomatrix panel, control line on pin 6.

A few fixes to get it to compile using arduino ide 1.5.7

Could not get the progmem pointer array to reside in progmem if anyone knows why let me know.
  so made the progmem pointer array reside in normal memory and removed the pgm_read code

If you use the adafruit libraries from this repository you will need to download them all as they are an interconnected work in progress.

But you can still use the original adafruit (GFX, NeoMatrix, NeoPixel) libraries with this test program

for more information

https://learn.adafruit.com/piccolo/overview
