# *I/O Switch & LED arrays* Module Board
4-switch input array and 4-led output array module board.
<br>
This input/output MOB is composed of two submodules, one consisting of 4 "active-low" input switches (for each switch current is limited to 0.5mA on 5V PSU), 
the other consisting of 4 "active-high" output LEDs (for each LED the current is limited to 5mA on 5V PSU).

![mob-built](mob-io-array-switch-and-led-4x_built.jpg)


## Schematic
![mob-schematic](mob-io-array-switch-and-led-4x_sch.jpg)


## PCB Layout
![mob-pcb](mob-io-array-switch-and-led-4x_pcb.jpg)


## Bill of Materials
- [x] paperboard 5x7cm
- [x] 2-pin (Molex-KK) power connector
- [x] bulk capacitor (tantalum) 10uF 16V
- [x] led current limiter resistor 1Kohm
- [x] power activity led green 3mm

- [x] 2 x 4-pin (Molex-KK) data connectors
- [x] 4 x data activity led current limiter resistors 1Kohm
- [x] 4 x data activity led green 3mm
- [x] 4 x pull-up resistor 10Kohm
- [x] 4 x data switch SPST (NO)