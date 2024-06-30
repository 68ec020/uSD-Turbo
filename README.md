# BBC Micro TurboMMC Interface

Use with
https://github.com/hoglet67/MMFS


Inspired by
http://stardot.org.uk/forums/viewtopic.php?t=9445&f=3#p110691

The interface works in my BBC Micro. I included resisters everywhere two outputs could be active at the same time, like in the hand-drawn schematic. So it should be safe. But: Use at your own risk!

## Changes compared to the hand-drawn schematic

* active level shifters (74LVC125AD) instead of voltage dividers
* 3.3 V voltage regulator
* no pull-ups on PB2, PB3, PB4, marked with VDD ? in the hand-drawn schematic (maybe I should add them, if the port is configured as input)

## Build your own

I ordered PCD from JLCPCB. Just use the file jlcpcb/production_files/GERBER-uSD-Turbo.zip

Uses the HTML-based BOM tool in /bom

I bought a microSD card slot on eBay, but I don't have a specific part number.

Make sure the right angle connector is mounted like in the 2D rendering. Pin 1 is the sqare pad. Make sure this corresponds with pin 1 of your port!

![uSD-Turbo](https://github.com/68ec020/uSD-Turbo/assets/877187/bb8985e3-056a-4dd1-b346-4e22e1a94e4c)
