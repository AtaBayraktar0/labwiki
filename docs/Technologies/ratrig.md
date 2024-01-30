---
layout: default
title: RatRig Vcore 50cm 
nav_exclude: true
has_children: false
permalink: /docs/technologies/ratrig
---
# RatRig

Useful information for operation and maintenance of our Rat Rig 50x50x50.

### Useful Links
1. [Rat Rig V-Core3.1 Details](https://docs.ratrig.com/product-details/v-core3-1)

## Sending print to Rat rig
### SUPERSLICER SETUP
1. Download latest release of Super Slicer [Download](https://github.com/supermerill/SuperSlicer/releases)
2. Set up printer as RatRig-V-Core-3-500
3. Set the filament to PETG / PLA
4. Go to printer settings and change following fan speeds on expert mode

| Setting  | value |
| ----------------- | -- |
| Bridges fan speed    | 40% |
| Max fan speed     | 40% |
 
### RAT RIG SETUP
Connecting to Rat OS network on your computer.
1. Go to the WiFi settings on your computer and connect to **RatOS**
 
| Wifi       | RatOS        |
| ---------- | ------------ |
| Password   | raspberry    |

2. Next, on the internet browser window type in following IP address
192.168.50.1

3. You should be now connected to the Rat Rig console on your browser.
4. Uplaod the Gcode and Print ! 
