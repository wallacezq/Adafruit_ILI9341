README
======

This is a fork of Adafruit ILI9341 Library for Intel Galileo.

**Limitation**: The screen is reacting rather slowly due to the poor I/O bandwidth provided by the I/O expander. 
	    I/O performance can be improved significantly by cutting the board traces so that the D/C pin connect directly to one of the native GPIO coming out from Intel Quark SoC.
	    
Note: The Arduino.h file (**[arduinoidefolder]**\hardware\arduino\x86\cores\arduino) need to be replaced with the one included in the *\Arduino* folder of this project. 

![text](http://i1266.photobucket.com/albums/jj531/wallace1zq/th_20140627_100348_zpsf47351c3.jpg)

---
*~This is the original readme from Adafruit ILI9341 project~*

```
This is a library for the Adafruit ILI9341 display products

This library works with the Adafruit 2.8" Touch Shield V2 (SPI)
  ----> http://www.adafruit.com/products/1651
 
Check out the links above for our tutorials and wiring diagrams.
These displays use SPI to communicate, 4 or 5 pins are required
to interface (RST is optional).

Adafruit invests time and resources providing this open source code,
please support Adafruit and open-source hardware by purchasing
products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.
MIT license, all text above must be included in any redistribution

To download. click the DOWNLOADS button in the top right corner, rename the uncompressed folder Adafruit_ILI9341. Check that the Adafruit_ILI9341 folder contains Adafruit_ILI9341.cpp and Adafruit_ILI9341.

Place the Adafruit_ILI9341 library folder your arduinosketchfolder/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE

Also requires the Adafruit_GFX library for Arduino.
```
