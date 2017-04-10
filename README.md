# PGA44 to DIP44 socket PCB project

## What is this?

* This is very simple electric circuit diagram on EAGLE CAD.
* This is my first trial for learn how to use EAGLE CAD.
* I made for prototyping CPLD device (Xilinx XC95 series) on the breadboards.

## Artworks

* Xilinx XC9536/XC9572 version
TODO: Xilinx XC9536/XC9572 version.

* Side-by-side pure converter version
![Side-by-side pure converter version](PGA44DIP44_pure-converter.png)

## How to use

### Xilinx XC9536/XC9572 version

TODO: More improving...

* You have to solder PGA44-PLCC44 socket and DIP22 x 2 headers.
* If your usage is side by side mapped pin conversion, you have to no additional works.
* If your usage is Xilinx XC95 series, add jumper pin header to head of board and solder x2 path-capacitors (ex: 0.1uF) onto SMD jumpers bottom of center board.
  * SMD jumpers shorts circuit between 21-41(VCCINT), 23-10-31(GND).
  * If jumper pin header closed, it shorts circuit between VCCINT and VCCIO. It means commonly voltage usage.

TODO: Example solder photos.

### Side-by-side pure converter version

* You have to solder PGA44-PLCC44 socket and DIP22 x 2 headers.
* Done!

TODO: Example solder photos.

## LICENSE

* [Under CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## History

* 1.1
  * Fatal misassignement fixed for PGA44.
  * Split simple side-by-side pure converter version (see also pure-converter branch).
* 1.0
  * First public release.
