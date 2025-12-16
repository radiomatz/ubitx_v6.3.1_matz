# ubitxv6.1m
uBitx v6.3.1m Arduino sketch
IMPORTANT: It will compile only if you place this in the Arduino's own sketch directory! This is because of the restricted places that the Arduino searches for it's include files (the headers).

ALSO, the file named *.ino, which is the main file, has to name same as folder, bla.ino -> folder bla.

- This is refactored to remove dependencies on any library except the standard Arduino libraries of SPI, I2C, EEPROM, etc.
- This works with ILI9341 display controller. The pins used by the TFT display are the same as that of the 16x2 LCD display of the previous versions.
- As the files are now split into .cpp files, the nano gui, morse reader, etc. can be reused in other projects as well

- modified by DM2HR:
  - finer tuning (10Hz)
  - remember setting of Frequency Adjustment
  - cw messages only, when in cw mode

TIP: for tuning freqency, set VFO A and B to same QRG; VFO A to LSB, VFO B to USB or vice versa; hear with a oscillator(best on 20MHz und up) on tone difference when switching A/B and adjust till difference is not more hearable.

uBITx needs about 20 Minutes in a normal warm room to get its QRG stable - dont adjust before!

This is released under GPL v3 license.
