---
layout: post
title: Betaflight 3.0!
tags: [polystack]
---
tl;dr Betaflight 3.0 is now [available](https://github.com/chickadee-tech/betaflight/releases/tag/v3.0.0) for the Chickadee Tech F3FC and F4FC. Still haven't bought a Polystack? Buy one (or more) to celebrate 3.0 with 20% off when you enter BETAFLIGHT30 in the cart.

I'm not going to recap everything thats in Betaflight 3.0 so check out the [release notes](https://github.com/chickadee-tech/betaflight/releases/tag/v3.0.0). I will cover the largest addition though because it had a huge impact on Polystack development.

The key feature of Betaflight 3.0 is F4 support. What does that mean? Well, prior to 3.0 Betaflight only supported F1 and F3 series microcontrollers from STMicroelectronics. (You can see their full line [here](http://www.st.com/content/st_com/en/products/microcontrollers.html).) One of the key differences between the F4 and the F1 and F3 is that its clock speed is 168MHz versus 72MHz. This means that Betaflight can do more in the same time as the F3s can. This also means that the same code takes less time to run. So, the time between the gyro read and PID output can be twice as fast. This is a big step for Betaflight.

When I was testing the [F4FC](https://chickadee.tech/f4fc/v5) in the spring I used [Raceflight](http://raceflightinfo.com/). At the time it was still open source but soon after they switched to a closed source development model. They continue to develop in a closed way. This was an issue for me, I created open source hardware and wanted to run open source software on it too. I wanted to be able to support Polystack's software which I wouldn't be able to do with Raceflight. So, I reached out to a couple of the other F4 flight control devs and double checked with Boris that he'd accept pull requests with F4 support. He said yes.

Jason Blackman, developer of the [BluejayF4](https://bluejayrc.com/), did the vast majority of the work. He is a rock star. If you don't want a modular flight controller I suggest you support him for his awesome work.

Overall, [Betaflight](https://github.com/betaflight/betaflight) is a great open source software project. There are many rock star developers who work on it and deserve mondo credit. Its incredible how far its come. Please check out the [release notes](https://github.com/chickadee-tech/betaflight/releases/tag/v3.0.0) which list some (but not all) of the awesome Betaflight contributors. This is what its all about.
