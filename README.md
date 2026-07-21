# CIB - Flapjack Octopus

[![License: CC BY-NC-SA](https://img.shields.io/badge/License-CC_BY--NC--SA-purple.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Hardware: CERN-OHL-S](https://img.shields.io/badge/License-CERN--OHL--S--2.0-purple)](https://gitlab.com/ohwr/project/cernohl/-/wikis/uploads/819d71bea3458f71fba6cf4fb0f2de6b/cern_ohl_s_v2.txt)

This is a KiCad and software project

[![By Ed Bowlby, NOAA/Olympic Coast NMS; NOAA/OAR/Office of Ocean Exploration - NOAA Photo Library, Public Domain](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/Opisthoteuthis_californiana.jpg/250px-Opisthoteuthis_californiana.jpg)](https://commons.wikimedia.org/w/index.php?curid=11244142)





Breakout board for Labjack T7

### Flapjack Octopus -- Labjack T7 Breakout

This is a breakout PCB for a Labjack T7, with 2.5 mm pitch screw headers to allow for quick wiring to the breakout PCB.

  * Digital IO ports are 5 V tolerant, there is no additional protection on the PCB.
  * Digital IO on ports C, E, F and M each have an LED that illuminates when 5V DC is applied
  * Digital IO port F is also set up as eight relay outputs, allowing up to eight 12/24 V (separate power supply required) to be driven from the T7 Labjack
  * Analogue in ports are taken via a potential divider to allow prescaling if required.
  * Additional terminals are available for 5V and Ground, as well as other pins, these are on the lower edge.