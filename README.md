SPIFlash
========

Fork of https://github.com/LowPowerLab/SPIFlash.

This version fixes wakeup() functionality such that it does not wait for the flash chip to be not busy
before it attempts to wake the flash chip from sleep.

Arduino library for read/write access to SPI flash memory chips.
See code files for initial documentation, more to come soon.

###Installation
Copy the content of this library in the "Arduino/libraries/SPIFlash" folder.
<br />
To find your Arduino folder go to File>Preferences in the Arduino IDE.
<br/>
See [this tutorial](http://learn.adafruit.com/arduino-tips-tricks-and-techniques/arduino-libraries) on Arduino libraries.
