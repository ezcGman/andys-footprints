# Andy's Footprints
While designing some PCBs, I ended up creating a few footprints myself. A few are completely done by myself, a few are just copied and slightly changed from the KiCad library

## BatteryHolder_Keystone_2460_1xAA-removed-holes
This is a copy from the `BatteryHolder_Keystone_2460_1xAA` footprint. I just removed the extra holes there in the PCB which I found unnecessary.

## ESP-07-Socket
This is a selfmade footprint. It's meant to hold an ESP-07 module on 2mm pin headers, so you can easily remove it again, if you want to. So simply stick it on and remove again :)
It's meant to work with the `RF_Module:ESP-07` schematic symbol.

## ESP-07-Socket-Cutout
Same as above, just the border I've drawn on the silk screen is shorter which allows you to do a cutout in the PCB right above it. This is not so useful for the ESP-07, but if you also want to support the ESP-12, which has a board antenna, so the board cutout would allow for a better Wi-Fi signal.

## ESP-12-Socket
Basically like the ESP-07, but it has a different pad numbering: The ESP-07 is missing the pins that the ESP-12 has on the bottom. So the ESP-07 footprint has a continious pad numbering from 1-16, while this one here has the left row numbered 1-8 and the right row 15-22.
It's meant to work with the `RF_Module:ESP-12E/F` schematic symbol.

## ESP-12-Socket-Cutout
Same as the ESP-12 footprint but again: Made the border on the silk screen shorter to allow for an antenna cutout in the PCB.

## Fuse_1808_4520Metric
A footprint I made myself (because I couldn't find a matching one in the KiCad library) for these 1808 SMD fuse holders: https://www.aliexpress.com/item/32869829922.html

![Fuse_1808_4520Metric](https://github.com/ezcGman/andys-footprints/blob/master/pictures/Fuse_1808_4520Metric.png?raw=true)
![Fuse_1808_4520Metric Outline](https://github.com/ezcGman/andys-footprints/blob/master/pictures/Fuse_1808_4520Metric-outline.png?raw=true)

## Grove-Connector-1x04-2.00mm-SMD-Horizontal
Again selfmade. A connector famously used on the M5 Stack Atom ESP32 modules

## M5-Stack-Atomic-DIY-Proto-PCB-With-Mounting-Hole
More selfmade. Bit similar to the ESP-07/ESP-12 socket, these are simply pin headers in the correct positions to stick an M5 Stack Atom on them, plus the mounting hole that sits below the Atom.

## PinHeader_1x03_P2.54mm_Vertical-Fixed-SilkScreen
Just a copy of the `PinHeader_1x03_P2.54mm_Vertical` footprint from the KiCad library. I just changed the silk screen a bit as I found it weird that the top pad is so "lonely" :)

## PinHeader_1x08_P2.54mm_Horizontal-Less-SilkScreen
Again a copy, this time from the `PinHeader_1x08_P2.54mm_Horizontal` footprint. I removed some of the silk screen, as if you mount this one at the edge of the board, that original silk screen looks really weird and broken. So I removed it

## PinHeader_1x08_P2.54mm_Vertical-Fixed-SilkScreen-Fixed-SilkScreen
Copy again, now from the `PinHeader_1x08_P2.54mm_Vertical-Fixed`. Same as the other "fixed": I just changed that top pad silk screen.

## PinHeader_2x04_P2.54mm_Horizontal-Less-SilkScreen
More copies: `PinHeader_2x04_P2.54mm_Horizontal`. Same story as the other "horizontal": If that one is at the edge of the board, the original silk screen looks broken.

## TerminalBlock_Phoenix_MPT-0,5-2-2.54_1x02_P2.54mm_Horizontal-removed-extra-holes
I love changing existing footprints: `TerminalBlock_Phoenix_MPT-0,5-2-2.54_1x02_P2.54mm_Horizontal`. This one also had two weird extra holes I don't understand what they were for: Deleted them.
