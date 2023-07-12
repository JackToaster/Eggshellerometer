# Eggshellerometer
![kibot](https://github.com/JackToaster/Eggshellerometer/actions/workflows/kibot.yml/badge.svg)

An acceleration-logging smart egg for egg drop experiments.

## Features
The goal of this project is to create a logging high-acceleration accelerometer. It can be used in place of an egg for egg-drop type experiments, and also as an open-source, hackable tool for recording high-acceleration events such as impacts or rocket launches. 
- 200G Accelerometer recording data at up to 3.2kHz (ADXL375)
- Built-in wifi/bluetooth with an ESP32-S3 microcontroller - allows connection to a phone/tablet companion app to visualize data
- tiny 0.5" OLED display to display information
- Tiny form factor - 30x50mm PCB which fits in a case the size of a large chicken egg
- Battery powered with a USB-C connector for charging/updating
- Configurable wakeup threshold to record acceleration events over a long period of time without draining battery
- Low cost, <$20 assembled in small quantities
- Open-source hardware and firmware (WIP)
- No chickens harmed in the making

## Status of the project
Currently, only the electrical hardware has been designed. I will include firmware, CAD & 3D printing files for enclosures, and any other information in this repository as I create them (Likely after I receive the first batch of prototypes).
