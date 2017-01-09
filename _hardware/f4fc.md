---
layout: page
permalink: /f4fc/v5
title: F4FC
tag: polystack
---

The F4FC is the bleeding edge of flight controller performance with a 168mhz STM32F4 microcontroller and MPU-6000 connected over SPI. The F4FC runs Betaflight 3.0 straight from [GitHub](https://github.com/chickadee-tech/betaflight) to live on the edge. The extra CPU speed gives this FC more potential than F3 based FCs. Its early days.

If you are a <strong>beginner</strong> or <strong>stability</strong> is important to you please start with a <a href="/f3fc/v9">F3FC</a>. All of the F4 software is very new and will need to be frequently updated for a while.

Stack up to seven Polystack mods to get all of the functionality you want now and in the future. No more buying a whole new flight controller just for a new feature. Polystack is open source to encourage a strong expansion ecosystem.

The F3FC comes loaded with an early version of Betaflight 3.0. Its recommended to update to the latest Betaflight available from https://github.com/chickadee-tech/betaflight/releases.

This includes all of the hardware you need to build a ~30mm Polystack. This should work well for most quads with 30mm standoffs. If your quad features shorter standoffs you will want to double check the distance you have from below the bottom plate to the bottom of the top plate (unless the top plate has matching holes). If your bottom plate if very thick or the standoffs are taller than 30mm you may want to buy extra 35mm screws to allow you to stack higher.

## Specifications

* Retail Price: $75
* STM32F405VGT6 168mhz, 1024KB Flash Memory, 192 KB SRAM
* MPU-6000
* Polystack connector with:
    * 6 hardware serial
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
* 4 High Quality Silver M3 x 0.5 7075 T6 Aluminum nylon locker nut
* 4 + 1 extra 3.5mm nylon spacer
* 8 + 1 extra nylon hex nut
* 4 1x2 housings for ESC signal wires
* 1 2x4 right angle headers
* 4 + 1 extra ~2mm nylon spacer

## Not Included

* Polystack power board
* Polystack receiver mod

## Links

* [Getting Started](https://github.com/chickadee-tech/f4fc/wiki/Getting-Started)
* [Betaflight Releases](https://github.com/chickadee-tech/betaflight/releases)
* [Source Files](https://github.com/chickadee-tech/f4fc)
* [Videos](https://www.youtube.com/playlist?list=PLc5VBJtwRhC9_mHcMzlGK0xwaXPWT6sEZ)
* [Raceflight (outdated)](https://github.com/chickadee-tech/raceflight)
