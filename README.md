# ADF-10 Style Econet module for Acorn computers
A fully compatible through hole version of the original Acorn ADF-10 Econet module.

Some general notes:

* Suitable for use with any Acorn Master series, Archimedes series and other devices that would accept the original Acorn ADF-10 Econet module.
* The dimensions of the module differ very slightly from the original ADF-10 module. Instead, it matches the outline of the Raspberry Pi models 2, 3 & 4 and has been specifically designed to fit on other PCBs (eg PiEconetBridge V1) that are designed to work the the Raspberry Pi.
* The source files are to be used with KiCAD v9.0.0 or later.
* The gerber files have been optimised for fabrication by JLCPCB. In particular, there is a 8mmx8mm silkscreen box on the rear of the PCB. This is to allow a 2D barcode, with unique serial number to be printed on the PCB.
* If you want the barcode to be added, then make sure to select this option in the 'Mark on PCB' field, and make sure to select 'Specify position' in the '2D Barcode Position' field, otherwise you will end up with a white 8mm x 8mm box printed on your PCB and a 8mm x 8mm barcode printed at a position of JLCPCBs choosing. Thrust me on this!
* If you don't want the barcode added, then remove the 8mm x 8mm box from the silkscreen layer and regenerate the gerbers. Otherwise you will end up with a white 8mm x 8mm box printed on your PCB.

Please refer to the following discussion on Stardot for further details: https://stardot.org.uk/forums/viewtopic.php?p=327138#p327138

## Author

The Mini Econet module is developed and maintained by Ken Lowe.
    
## Hardware License (Creative Commons BY-SA 4.0)

Please see the following link for details: https://creativecommons.org/licenses/by-sa/4.0/

You are free to:

Share - copy and redistribute the material in any medium or format
Adapt - remix, transform, and build upon the material
for any purpose, even commercially.

This license is acceptable for Free Cultural Works.

The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

Attribution - You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

ShareAlike - If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions - You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
