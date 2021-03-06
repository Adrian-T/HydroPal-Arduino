# HydroPal: Arduino Code

## Description
This is the Arduino code for the HydroPal smart water bottle JA company. The code will primarily allow the Arduino Nano board to read the ml/sec of liquids going though the nozzle of the bottle in order to measure the millitres of water that a person drinks throughout the day.

## Setting up
If you are using a Mac with an Arduino with a CH34x USB chip, install the driver above. Then upload the code to the Arduino and change ports as required.

## Current Functionality
- Checks sensor reading every second to find ml/sec passing through sensor
- Adds sensor reading to total ml of liquid consumed throughout the day
- Converts ml to L after 1 L is reached

## To-do
- Reset total counter midnight every day
- Indicate total consumption and/or percentage of goal achieved everyday
- Simple serial calibration for more accurate readings

## Future functionality
- Bluetooth sync with mobile device
