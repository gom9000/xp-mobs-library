# module-boards-library

commit form: Maintenance/Feature/Bugfix release


## 1.0.0 "*Basic*" 2019-10-30 Feature release
The "Basic" release collects a set of self-consistent boards (mobs) to provide power supply, provide digital inputs and show outputs of basic electronic projects, perhaps based on Microchip PIC16f6x8.
(used by xp-pic-assembly)
- Added MOB mob-io-7seg-bcd
- Added MOB mob-io-7seg
- Added "Basic" MOBs library overview image




1) ExpressPCB Custom Library:
	rename TEBO custom components to MOB components;
	change Power Jack SCH;
	verify ALL!!!

2) for MOB:
	rename sch & pcb files;
	change "Test Board" with "Module Boards Library";
	change pcb label;
	change TEBO custom components to MOB components;
	create README file with mob description, specifics, built photo, sch and pcb picture, bom and test;
	update mobs-library README file with the new mob.


- old tebo modules:
* [mob-4bit-7seg](mobs/mob-4bit-7seg/) : 7-segment display with BCD input module board
* [mob-8bit-7seg](mobs/mob-8bit-7seg/) : 7-segment display module board

* [tebo-if-rs232](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-rs232/) : rs232 interface v1.0
* [tebo-if-midi](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-midi/) : midi-in/out/thru interface v1.3
* [tebo-if-midi-in](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-midi-in/) : midi-in interface v1.3
* [tebo-if-midi-in-x2](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-midi-in-x2/) : two input midi-in interface v1.0
* [tebo-if-midi-out](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-midi-out/) : midi-out interface v1.3
* [tebo-if-midi-out-x2](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-midi-out-x2/) : two output midi-out interface v1.0
* [tebo-if-fdd](https://github.com/gos95-electronics/test-boards-library/tree/master/tebo-if-fdd/) : Floppy Disk Drive interface v1.1


Future MOBs
-----------
- mob-psu-*
	mob-psu-3v
	mob-psu-9v
	(mob-psu-9-0-9)
	(mob-psu-15-0-15)
- mob-mcu-*
	mob-mcu-16f8x7
	(mob-pic12f683)
- mob-if-*
	mob-if-midi*
	mob-if-rs232
	(mob-if-fdd)
	mob-if-backplane-4bit
	mob-if-backplane-8bit	
- mob-io-*
	mob-io-7seg-bcd
	mob-io-7seg-bcd-2x
	mob-io-7seg
	mob-io-7seg-2x
	mob-io-7seg-3x
	mob-io-7seg-4x
	mob-io-array-led-4x
	mob-io-array-led-8x
	mob-io-array-switch-4x
	mob-io-array-switch-8x
	mob-io-array-dipswitch-8x
	mob-io-matrix-led-4x4
	mob-io-matrix-switch-4x4
- mob-fn-*
	mob-fn-buffer-8x
	mob-fn-dac-4bit
	mob-fn-dac-8bit
	mob-fn-decoder-3-8
	mob-fn-decoder-4-16
	mob-fn-not-8bit
	mob-fn-clock-32.768-khz
	mob-fn-clock-8.1-12-24.4-khz
	mob-fn-clock-32.125-mhz

- mob-io-lcd-16x2