ZMK config - https://github.com/gehennaXXIV/zmk-config-Doro62

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
| Nice Nanos                     |  02   |  or NRF52840
| Li-Po Battery                  |  01   |  TAKE NOTE OF THE POLARITY BEFORE PLUGGING IT IN [Here's a tutorial on how to change the polarity.](https://www.youtube.com/watch?v=za-azgbZor8)

***
| **CASE**                           |  Qty  |  Remarks |
| :--------------------- 		         | :---: | :------  |
| [Acrylic Case](/Case/)             |  02   |          |
| M2 8mm Wafer Head Screws		       |  24   | If you want to increase the distance from plate to top of case, might need to increase the length of the screws as well.
| M2 9mm Round Standoff Spacer       |  12   |          |
| Rubber Feet					               |  08   | Currently the keyboard lays flat, I've yet to design a base layer for angled feet |
