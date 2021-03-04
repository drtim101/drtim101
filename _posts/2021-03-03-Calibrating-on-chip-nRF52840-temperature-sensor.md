---
layout: post
title:  "Calibrating on chip nRF52840 temperature sensor"
date:   2021-03-03 13:17:47 +0000
categories: jekyll update
---

# About

I want some simple wireless temperature sensors for various domestic applications such as providing inputs to house central heating control and logging ferment temperature while brewing. I have various Nordic BLE MCUs that have onboard (die) temperature sensors. How accurate are these? Starting with nRF52840 dongle modules.

## Methods

- Two wireless MCUs one with external temperature sensor, one without. 
- Each is programmed to connect to a central basestation that periodically requests temperature readings from each. 
- Both devices are located in close proximity. 
- Readings are taken every 6 minutes and logged over a 48 hour period. 
- The results are plotted in an XY graph and the correlation / regression line calculated.
- The accuracy of the external sensor is .. 

## Results

<img src="{{site.baseurl}}/assets/images/dog.jpg">

