# SpliX ML-1860/1865 and ML-1670 PPD
My custom PPDs to make Samsung ML-1860/1865 and ML-1670/1675 printer work with [SpliX](http://splix.ap2c.org/). Tested and working on Raspberry Pi.

Manual duplex is working as intended (ml1860.ppd or ml1670_with_manual_duplex.ppd). A4 is the default paper size.

## Installation
Make sure you have SpliX installed on your system, e.g.
```
sudo apt-get install printer-driver-splix
```
Go to CUPS admin page (somehost:631) and select this PPD for the printer.

## License
GPLv2
