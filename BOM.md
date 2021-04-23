# Bill of Materials for PowerBook adapter for BlueSCSI

https://github.com/xunker/bluescsi_pb/BOM.md

To assemble v1.1 the board, you will need the following components:

## Required

Quantity | Thing | Example Part Number
---------|-------|--------------------
1        | An STM32 "Blue Pill" module and a way to program it with the [BlueSCSI](https://github.com/erichelgeson/BlueSCSI) firmware |
2        | 330 Ohm Resistor Network in SIP-10 package | Bourns 4610X-101-331
2        | 220 Ohm Resistor Network in SIP-10 package | Bourns 4610X-101-221
1        | MicroSD Card connector (or use SD-to-MicroSD adapter [as shown here](README.md#microsd-card-j3-and-sd-card-breakout-j7)) |  Molex 104031-0811
1        | 2x20 right-angle **2mm** header for connector J1 |
2        | 1x2 header pins for the termination jumper connectors J4 and J5 |
2        | Jumpers (aka jumper caps, shunts, or shorts) for J4 and J5 |

## Optional

Quantity | Thing
---------|-------
1        | 1x4 2.54mm right-angle header for debugging connector
2        | 1x2 header pins for the power selection jumper connectors J9 and J10
1        | 2x25 2.54 header pins for 50-pin desktop SCSI connector J8
1        | LED for D1
1        | Resistor (R1) for LED, any value from 330 ohms to about 1.8k ohms will work
2        | ["low-profile" female headers](https://www.adafruit.com/product/3008) if you do not want to permanently solder the Blue Pill board


