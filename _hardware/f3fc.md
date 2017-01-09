---
layout: page
permalink: /f3fc/v9
title: F3FC
tag: polystack
---

The F3FC features exceptional performance with a 72mhz STM32F3 microcontroller and MPU-6000 connected over SPI. It has more connectivity than all other flight controllers except its sibling F4FC through the Polystack connector. Four PWM motor outputs are built into the board.

Stack up to seven Polystack mods (height permitting) to get all of the functionality you want now and in the future. No more buying a whole new flight controller just for a new feature. Add a microSD mod for blackbox or a microMinimOSD cradle for OSD. Polystack is open source to encourage a strong mod ecosystem.

The F3FC comes loaded with an early version of Betaflight 3.0. Its recommended to update to the latest Betaflight available from https://github.com/chickadee-tech/betaflight/releases.

This includes all of the hardware you need to build a ~30mm Polystack. This should work well for most quads with 30mm standoffs. If your quad features shorter standoffs you will want to double check the distance you have from below the bottom plate to the bottom of the top plate (unless the top plate has matching holes). If your bottom plate if very thick or the standoffs are taller than 30mm you may want to buy extra 35mm screws to allow you to stack higher.

## Specifications

* Retail Price: $60
* STM32F303VCT6 72mhz Arm Cortex M4 with FPU, 256KB Flash Memory, 40KB SRAM
* MPU-6000
* Polystack connector with:
    * 5 hardware serial
    * 2 SPI
    * 1 shared i2c
    * 4 individual timers (good for PPM, servos and LED)
    * 2 groups of four timers (good for PWM inputs and outputs)
    * 2 ADC
    * 6 GPIO
* USB VCP
* 3.5 mm Stacking Height
* 36mm x 36mm Footprint with 30.5mm x 30.5mm mounting holes

## Included
* 4 High Quality Silver M3 x 0.5 x 30mm 7075 T6 Aluminum screws
* 4 + 1 extra 3.5mm nylon spacer
* 8 + 1 extra nylon hex nut
* 4 1x2 housings for ESC signal wires
* 1 2x4 right angle headers
* 4 + 1 extra ~2mm nylon spacer

## Not Included
* Polystack power board
* Polystack receiver mod

## Links
* [Getting Started](https://github.com/chickadee-tech/f3fc/wiki/Getting-Started)
* [Betaflight Releases](https://github.com/chickadee-tech/betaflight/releases)
* [Source Files](https://github.com/chickadee-tech/f3fc)
* [Videos](https://www.youtube.com/playlist?list=PLc5VBJtwRhC--RGb7noFgptZvLtrV7_h4)
