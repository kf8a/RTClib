This is a fork of JeeLab's fantastic real time clock library for Arduino.

This version uses https://github.com/DSSCircuits/I2C-Master-Library instead of the wire library to support timeouts.

WARNING
-------
Currently this only implements the now() and adjust() functions.


For details on using this library with an RTC module like the DS1307, see the guide at: https://learn.adafruit.com/ds1307-real-time-clock-breakout-board-kit/overview

To download. click the DOWNLOADS button to the right, and rename the uncompressed folder RTClib.

Place the RTClib folder in your *arduinosketchfolder*/libraries/ folder. 
You may need to create the libraries subfolder if its your first library. Restart the IDE.
