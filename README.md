# Collection of scripts for Raspberry Pi

This repository contains my collection of useful scripts for Raspberry Pi.


## Installation on Raspbian Jessie

1. Clone repository into your home directory.

        git clone git@github.com:gszasz/rpi-scripts.git


2. Create `~/bin` directory

        mkdir ~/bin


3. Create following link(s) for individual scripts:

        ln -sf ~/rpi-scripts/rpi-temp ~/bin/rpi-temp


## Scripts

### rpi-temp.sh

A simple shell script derived from the my-pi-temp.sh by Vivek Gite [1,2] that
just displays both GPU and CPU temperature of Raspberry Pi 2.

[1] http://www.cyberciti.biz
[2] https://www.cyberciti.biz/faq/linux-find-out-raspberry-pi-gpu-and-arm-cpu-temperature-command/
