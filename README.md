# Doro62
***
![Image](/pics/build.jpg)


[ZMK config](https://github.com/gehennaXXIV/zmk-config-Doro62) - It has a supporting json file for https://nickcoutsos.github.io/keymap-editor/ 

[QMK config](https://github.com/gehennaXXIV/qmk-config-GHN) - RP2040 Pro Micro w/ Vial support


***
## PARTS
| **COMPONENTS**             |  Qty  |  Remarks |
| :--------------------- 		 | :---: | :------  |
| Diodes 1N4148W (SMD)	 		 |  62   | SOD-123  |
| MX Switch Sockets				   |  62   |          |
| 2U PCB-Mount Stabilizers   |  03   |          |
| Power Switch					     |  01   | MSK12C02 |
| Reset Switch 		 			     |  01   | MJTP1250, this is soldered to the bottom of the PCB |
| JST 2 PH Right Angle Jack	 |  01   |          |
***
| **MCU**                        |  Qty  |  Remarks |
| :--------------------- 		     | :---: | :------  |
| Low Profile MCU sockets        |  04   |  Does not need to be expensive millmax sockets, the mcu socket footprint was modified to allow [sockets with thick pins to work](https://down-ph.img.susercontent.com/file/sg-11134201-7qvco-ley7fi4ef44v33)
| Mill Max Pins					         |  48   |  Mouser 3320-0-00-15-00-00-03-0, or a cheaper one, harvested gold pins 5pin RGB header (just snip off the plastic parts)
| Nice Nanos                     |  01   |  or NRF52840
| Li-Po Battery                  |  01   |  TAKE NOTE OF THE POLARITY BEFORE PLUGGING IT IN [Here's a tutorial on how to change the polarity.](https://www.youtube.com/watch?v=za-azgbZor8)

***
| **CASE**                           |  Qty  |  Remarks |
| :--------------------- 		         | :---: | :------  |
| [Acrylic Case](/Case/)             |  01   | maybe a 3DP one soon, but I'm very content with the acrylic case. LMK if you create one! |
| M2 8mm Wafer Head Screws		       |  24   | If you want to increase the distance from plate to top of case, might need to increase the length of the screws as well.
| M2 12mm Round Standoff Spacer       |  12   |  Or 11 if it's portruding / giving plate a slight gap        |
| Rubber Feet					               |  08   | Currently the keyboard lays flat, I've yet to design a base layer for angled feet |

***
## FOOTPRINTS USED
* https://github.com/ebastler/marbastlib
* https://github.com/joe-scotto/scottokeebs
* https://github.com/GEIGEIGEIST/KLOR
* https://github.com/50an6xy06r6n/keyboard_reversible.pretty

***
Please note that while this keyboard is provided as open-source, I am not liable for any issues, malfunctions, or other problems that may arise from its use. The keyboard is provided "as-is," and I make no warranties or guarantees regarding its performance or functionality. Use at your own risk.

This is my first take at creating a keyboard from scratch, there's obviously alot of things that could've been done better. I will be redesigning this board in the future.