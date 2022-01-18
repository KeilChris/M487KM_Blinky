Blinky project
==============

The **Blinky** project can be easily used to verify the basic tool setup.

It is compliant to the [Cortex Microcontroller Software Interface Standard (CMSIS)](https://arm-software.github.io/CMSIS_5/General/html/index.html).

Operation
---------

- At start, LEDG and LEDR blink alternately in a 1 sec interval.
- Clock Settings:
  - XTAL =  12 MHz
  - CCLK = 192 MHz (PLLCLK)

Target
------

- **M487KMCAN Flash** is configured for on-chip Flash of the [NuMaker-M487KM board](https://www.nuvoton.com/board/numaker-pfm-m487km).
- If you want to yous it with the older NuMaker-PFM-M487, remove the M487KMCAN define from the project.