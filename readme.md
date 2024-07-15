# Breadboard LED Array

I created these LED Arrays for use in my construction of the internet famous [Ben Eater 8-bit Computer](https://eater.net/8bit), but they could be handy for any breadboard project that requires groups of 8 LEDs.

If you wish to make your own, the files for the PCB and links to the parts can be found below. Some assembly required.

![Breadboard LED Array - rendered by KiCad 7](artwork/3d-view-bg-blk.png | height=100) ![Breadboard LED Array - in situ](artwork/in-situ.png | height=100)

Go ahead. Laugh at my sloppy construction. I had a 3D printed assembly jig made after I did this one by hand. What a difference it made. Thanks, Luke!

## How to use

The pins are strategically arranged so you can connect the array directly to pins 2-9 (address lines) and pin 10 (ground) of a 74LS245 Bus Transceiver without any wires. To accomodate pinouts of other ICs, you could install a mix of jumper wires and header pins as needed. Use straight headers if you want the board to lie flat. I designed for minimum footprint, hence the 90° header.

The onboard resistor array limits the current to the LEDs so no external parts are needed. Use something like 680Ω, or go as high as 1k. You could use lower resistance if you like brighter LEDs but I wouldn't go below 270Ω.

## PCBs

This [GitHub repository](https://github.com/SonOfSofaman/BreadboardLEDArray) contains the [KiCad 7](https://www.kicad.org/) files for the circuit board. Also included are the Gerber files if you want to fabricate your own boards. See the /fab folder.

Use this [project link](https://oshpark.com/shared_projects/hIeStv3n) to purchase the boards from [OSH Park](https://oshpark.com/).

## Parts

Use this [parts list](https://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=65f5e81664) if you want to buy the LEDs and/or resistors from [Mouser](https://mouser.com).

[BreadboardLEDArray](https://github.com/SonOfSofaman/BreadboardLEDArray) © 2023 by [SofaTronics / SonOfSofaman](https://sofatronics.io/) is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1)
