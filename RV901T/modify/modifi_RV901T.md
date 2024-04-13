RV901T Modification
There are two options. 
The first one consists of:
1. removing of R608 resistor (upper part of the board)
2. cutting the track which goes to FPGA F13 pin,
3. solder the resistor (0805 1K) that will pull up to 5V upper segment of the track
4. cutting the track  (bottom right corner)
5. connecting its bottom part to GND polygon

The second one consist of:
1. cutting the track (bottom right corner)
2. connecting its bottom part to GND polygon
3. in FPGA "connect" F13 pin to Vcc

All of these options work.
