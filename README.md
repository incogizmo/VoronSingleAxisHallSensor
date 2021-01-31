# Single Axis Hall Sensor for Voron
This is a hall effect sensor based of the existing Voron hall effect sensor for Voron v2.
Designed to be a single axis only and fit within the Y endstop area of V1.8 and be small enough to be flexible for mounting options for X axis.

In this branch the output is Normally Closed. This will provide failsafes if the board / wiring fails, testing needs to be done to ensure accuracy in this configuration.

The comparator in this branch is different to maintain the same PCB layout.
![PCB](pcb.jpg)

NOTE: THIS IS UNTESTED AND I SUSPECT THERE IS AN ISSUE WITH THE CURRENT SCHEMATIC (SIGNAL ALWAYS SUNK TO GROUND), USE/ORDER AT YOUR OWN RISK

This is designed for use with Voron v1.8 printer: https://github.com/VoronDesign/ http://vorondesign.com/
