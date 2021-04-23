# Future plans for PowerBook adapter for BlueSCSI
# April 2021

https://github.com/xunker/bluescsi_pb/FUTURE_PLANS.md

[v1.1](v1.1) is working well so I don't expect any majour changes for a while.

## v1.2 (possible maintenance version)

Plans for a v1.2 (maintenance) may include:

* Jumper to toggle the activity LED
  - So you can solder the LED and resistor, but disable it later if you prefer
* Break out power LED
  - Provide a power LED (and a jumper toggle) breakout if an external power LED is desired
* Replace J4 & J5 with DIP switches or a single DPDT switch

## v2.0 (possible full redesign)

If I continue to develop project in the future, I plan on a full redesign.

* Use termination ICs instead of resistors
  - Lower power consumption
  - More accurate termination voltage
  - Switchable termination resistance (110-ohm or 2.5k-ohm) for short busses
* Attach J1 & J2 via the PCB edge to make it more like how an actual hard drive connects
* Less-expensive Micro SD card slot
* Automatic switching between TERMPWR, MOTORPWR or USB Power

If I want to fork the actual BlueSCSI firmware, I would like to add:

* Separate LEDs for read and write activity
* Read TERMPWR and MOTORPWR voltages and report them on the debugging connector
* LEDs to indicate with SCSI ID is being accessed
* Support OLED debugging display
