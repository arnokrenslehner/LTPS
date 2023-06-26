# LTPS
LTPS (**L**ow **T**emperature **P**ower **S**ystem) is a power supply board designed for high-altitude balloon applications.
It provides three step-up converters and load switches as well as an ADC which can be read via I2C. <br>
The smb connector on the upper left side is part of the "remove before flight" circuitry, you can use a shorted out smb plug to disable the whole
LTPS system.

![alt text](pictures/LTPS_renderview.jpg)

The board measures 120*100mm, its 4 layers.

## PCB Production and part procurement  
The design is optimized to the standard JLC-PCB 4-layer process.
I bought the parts from Mouser, all automotive types. Because it's just a private project 
I can't provide you with a "clean" BOM.

This version here incorporates all bugfixes from the first one I built:

![alt text](pictures/LTPS_topview.jpg)

One can see the bodge on the upper left of the PCB, I also fixed up some spacing, etc.

![alt text](pictures/LTPS_sideview.jpg)

The board is designed to hold three "SAFT M52 LiMnO2" cells which are ideal for high-altitude ballooning, but expensive, one can 
use some other (lithium cells) in "C" size.

Please consult the schematic and the according datasheets for modifications etc.
