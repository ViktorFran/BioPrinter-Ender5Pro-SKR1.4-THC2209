# Bio-printer firmware for Ender 5 pro 3D printer
Customised Marlin v2.0.x for SKR1.4Turbo with TMC2209 driver
2 extruder for hydrogel extrusion

firmware.bin file is created in .pio/build/"ControllerName"/firmware.bin when this file is built with PlatformIO

Copy the firmware.bin into SD card parent directory. 
Power the board, and if USB is connected, open serial monitor and run following commands in this order;
M502 //Default firmware setting
M500 //Store setting into EEPROM
M501 //Load setting from EEPROM


Troubleshooting
M119 //Report Endstop status
M122 //TMC driver debugging