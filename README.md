Audio Multi Filter
==================

Drawings and PCB (c) 2027 Andrew Martin, acramonics
---------------------------------------------------

This is an implementation of Jake Rothman's **Audio Multi Filter**
described in *Practical Electronics*, May 2026.

This circuit provides High-Pass, Low-Pass, Band-Pass, Notch and
All-Pass filters on a single circuit by combining combinations of
High-Pass and Low-Pass outputs.

In addition to the hardware on the board, my design requires:

- a 3P6T rotary switch,
- a DPDT (or DPST) toggle switch,
- a 10K anti-log pot,
- a dual 100K anti-log pot.


Power Supply
------------

The design includes power smoothing, but will need a dual rail power
supply providing somewhere between +/-12V and +/-18V.

Hardware
--------

### 3P6T rotary switch

The classical wafer switches are *extremely* expensive from UK
suppliers, typically #30.00 upwards per wafer! However, I have found
them at a very reasonable price (~#4.00) from AliExpress.

You could also use a 3P5T switch and replace the 1st straight through
position ('Thru') with another toggle switch.

For a stereo version, either build two boards, or if you want the same
output on both channels, you could use a 6P6T switch (if you can find
one), or a 6P5T switch (which I have seen on AliExpress at ~#5.00) and
a toggle switch to replace the Thru position.

