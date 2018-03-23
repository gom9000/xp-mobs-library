# Electronics Test Boards Library
Various modular-designed test boards created for home didactic electronics projects.<br>
These boards (TEBO) are useful for:
* testing specific components functions
* prototyping complex projects by modular approach
* expanding and interfacing components functions


## Recent Updates (2018-03-23)
* Add io-matrix-4x4 TEBOs


## Contents of the library
* [ExpressPCB custom components library](https://github.com/gos95-electronics/test-boards-library/tree/master/expresspcb/) containing the schematic and pcb components used for drawing the tebos layout
* [tebo-psu-5](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-psu-5/) : psu 5V v1.2
* [tebo-psu-distribution](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-psu-distribution/) : psu 8-lines distribution unit v1.0
* [tebo-fn-cbank-26.4mF](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-fn-cbank-26.4mF/) : 26400uF/10V capacitor bank v1.0
* [tebo-mcu-pic16f6x8](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-mcu-pic16f6x8/) : Microchip PIC 16F6x8 microcontroller board v1.1
* [tebo-io-switch-led-array-4](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-io-switch-led-array-4/) : 4-switch input array, 4-led output array v1.1
* [tebo-io-button-led-array-4](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-io-button-led-array-4/) : 4-button input array, 4 led output array v1.0
* [tebo-io-led-matrix-4x4](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-io-led-matrix-4x4/) : 4x4 output led matrix v1.0
* [tebo-io-switch-matrix-4x4](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-io-switch-matrix-4x4/) : 4x4 input switch matrix v1.0
* [tebo-if-rs232](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-rs232/) : rs232 interface v1.0
* [tebo-if-midi](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-midi/) : midi-in/out/thru interface v1.3
* [tebo-if-midi-in](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-midi-in/) : midi-in interface v1.3
* [tebo-if-midi-in-x2](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-midi-in-x2/) : two input midi-in interface v1.3
* [tebo-if-midi-out](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-midi-out/) : midi-out interface v1.3
* [tebo-if-fdd](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-fdd/) : Floppy Disk Drive interface v1.1


## Specifications
Schematics and PCB layouts are designed with ExpressPCB free CAD software.

### TEBO naming convention
* tebo (test board)
* tebo-psu (power supply unit tebo)
* tebo-io (input/output tebo)
* tebo-if (interface tebo)
* tebo-fn (function controller tebo)
* tebo-mcu (micro controller unit tebo)

### PCB Specifications
* PCB layout are designed for paperboard sizes: 2x8cm, 5x7cm, 7x10cm
* Each TEBO has the power connector (PWR) with the positive pin on left, a decoupling capacitor and a power-on led (yes, I have surplus of components!)
* Led colors and sizes are:
	* 3mm green led for power or (3/5mm) normal activity indicators
	* 3mm yellow led for warning status indicators
	* 3mm red led for error, fault or wrong status indicators
	* 3mm blue led for request for manual intervent
* Led current limiter resistors: R=1Kohm
* Digital pin pull-up resistors: R=10Kohm
* IC decoupling capacitors: C=100nF
* Board filtering and decoupling capacitors: C=10uF tantalum

### ExpressPCB Custom Conponents Library
* ExpressPCB components used for tebos are customized and named as "_TEBO-name-*size*"
* Paperboard layout templates are also saved as ExpressPCB custom components and named as "_TEBO-Paperboard-*size*"
* Components size units, where not specified, are 1/10 of inches (1/10 of inch = 1 Module Unit)
* PCB traces are 0.05", pads are 0,065"


## Future Plans for the TEBOs Library
* Include photos of built tebos
* Include technical specifications for each tebo
* Add more tebos


## Licence
The [MIT license](https://github.com/gos95-electronics/test-boards-library/blob/master/LICENSE/) posted in the main repository directory is applied to all the TEBOs and ExpressPCB custom components library.
You are free to use them for any purpose, just try to give credit in the documentation of your project.


## Questions/Comments
This is a home didactic project. If you have any questions, hints or comments please submit an issue with your question/hint/comment and I will get back to you as soon as I can.
