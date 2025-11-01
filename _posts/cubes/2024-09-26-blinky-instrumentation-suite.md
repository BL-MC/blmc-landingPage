---
layout: page-fullwidth
subheadline: "Instrumentation"
title:  "Blinky-Lite Instrumentation Suite"
teaser: "A modular approach to distrubuted instrumentation"
breadcrumb: true
tags:
    - post instrumentation
categories:
    - cubes
image:
    thumb: 2024-09-26/thumbnail.jpg
header: no
---
<div class="row t30">
    <img src="{{ site.urlimg }}/2024-09-26/BLInstSuite.jpg" >
</div>

For instrumentation to be useful, it needs to be easily and quickly installed wherever a user needs it to be. Blinky-Lite accomplishes this with a suite of wireless instrumentation modules based on the Raspberry Pi Pico-W, including:
- <span style="color:#fdc100;font-weight:900;">Blinky-ADC</span>
  - Two channel ADC
  - Range: 10V
  - Resolution:  0.002V 
  - 1Hz to 50 kHz of settable bandwidth
- <span style="color:#fdc100;font-weight:900;">Blinky-DS18B20</span>
  - Three channel high resolution temperature monitor.
  - Range: -50 to 125C 
  - Resolution: 0.05C
- <span style="color:#fdc100;font-weight:900;">Blinky-Interlock</span>
  - Three channels that can be used in thermal switches, motion detectors, magnetic switches, etc.
  - Daisy chain output for each channel provided. 
- <span style="color:#fdc100;font-weight:900;">Blinky-Leak</span>
  - Three leak detector channels
  - 20 MOhm sensitivity
- <span style="color:#fdc100;font-weight:900;">Blinky-420</span>
  - Three channel 4-20 mA convertor that can be reading for analog interfaces
  - Resolution: 0.004 mA
  - 1Hz to 50 kHz of settable bandwidth
- <span style="color:#fdc100;font-weight:900;">Blinky-Thermocouple</span>
  - Three channels K type thermocouple
  - Range: -200C - 1350C
  - Resolution: 0.25C
- <span style="color:#fdc100;font-weight:900;">Blinky-MAX31865</span>
  - Two channel 4 wire resistor measurement
  - Range: 0 to 4300 Ohms
  - Resolution: 0.1 Ohms
  - 100 mS pulse mode for minimal self heating
