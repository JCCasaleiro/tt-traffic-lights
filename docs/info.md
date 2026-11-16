<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A traffic light controller. It requires a clock signal to change the state of the FSM and an input that is the RST_N. If the RST_N is depressed the traffic light sequential changes from green to yellow and yellow to red. 

## How to test

Put a clock of 1Hz ate clock input

## External hardware

Need 5 LEDs: 2 Green, 2 Red and 1 Yellow. Three LEDs are for the vehicle lights and two for the pedestrians lights.   
