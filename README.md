## MicroSD Switch

This a derivative work of a similar project by Joel Agnel.  You can find
his original works that this is based on at:
https://github.com/joelagnel/microsd-switch

The main changes I made were to use 2x4 IDC headers instead of 1x8 rows,
and I also removed the usb/ftdi based switching in favor of a 40pin
connector so that I could use it as a RPI2/3 hat. It's not a proper hat
layout at the moment with eeprom or recommended board layout because it's
a work in progress, but the prototypes fit nicely as it is now.

To switch between host and target, it is currently wired to use GPIO 12
