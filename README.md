# Social security number 
By using Arduino Uno and a breadboard, the goal is to get my social security number displayed on a 7-segment display.

**Starting at zero**
- Connection of the 4-bit counter and adder.
- Connecting the 74HC161 4 bit counter, 74HC86 XOR and the 74HC283 4-bit full adder as the figure shows. 
- Connecting the Schmitt trigger clock to the Clock input. 
- Adiiing the 7 Segment Display and connecting it to the CD4543B 7 Segment Decoder.

**The project**
The 74HC138 activates one of its eight outputs “0” at a time, the other outputs are “1” but the diodes and the resistor will operate as an AND gate, so a diode will result in a “0”. However, after the inverter, this is a “1”, so a Diode represents a  “1”. The next step is to connect a Diode ROM Memory with my date of birth (8 digits). To display the date, I connect A B C of the decoder to the 74HC161 binary counter outputs QA QB QC.  
