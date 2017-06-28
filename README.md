# Collection of scripts for Raspberry Pi

This repository contains my collection of useful scripts for Raspberry Pi.


## Installation on Raspbian Jessie

1. Clone repository:

        git clone git@github.com:gszasz/rpi-scripts.git


2. Run installation script:

        cd rpi-scripts
        sudo ./install.sh


## Scripts

### rpi-temp

A simple shell script that just displays temperature of GPU and CPU.  It was
tested on Raspberry Pi 3, but it should work on Raspberry Pi 2 as well.

The `rpi-temp` script is derived from
 [my-pi-temp.sh](https://www.cyberciti.biz/faq/linux-find-out-raspberry-pi-gpu-and-arm-cpu-temperature-command/
 written by [Vivek Gite](http://www.cyberciti.biz).
