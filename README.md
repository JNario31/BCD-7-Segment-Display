# BCD-7-Segment-Display

Stack: Intel Quartus, Verilog HDL

Truth table of all possible binary combinations represented on 7-segment display:
[insert image]

Mapping each output from the 7-segments onto karnaugh maps and deriving boolean functions:
[insert image]

Then in quartus I implemented the logic circuits derived from the karnaugh mapping for each segment in the display.
The 4 inputs a,b,c,d were given pin assignments of sw3,sw2,sw1,sw0 respectively.
The outputs were given pin assingments:hex00, hex01, hex02, hex03, hex04, hex05, hex06.
