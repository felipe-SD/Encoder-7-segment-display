<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A BCD to 7-segment encoder is a digital logic circuit that converts
a Binary-Coded Decimal (BCD) input into signals that can drive a 7-segment display.
BCD represents decimal digits 0–9 in 4-bit binary:


## How to test

Outputs
7 segments of the display: a, b, c, d, e, f, g
Each output controls one segment. A high (1) signal lights up the segment, and low (0) turns it off.
Optional DP (decimal point) can also be controlled.

Working Principle
The circuit maps each BCD input to the combination of segments that 
forms the corresponding decimal digit on the 7-segment display.
For example, to display 0, segments a, b, c, d, e, f are ON, and g is OFF.
AND EXTRA GATES INCLUDE CONTROL OF POINT 

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
this uses default hardware, leds and logic input.
