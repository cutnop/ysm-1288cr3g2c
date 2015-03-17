
---

# Matrix Pins #

The pin-outs provided in the datasheet are confusing difficult to understand. The following images should help identify each pin as well as which pin connects to the correct MAX7221 pin.

[Datasheet](http://ysm-1288cr3g2c.googlecode.com/files/SanYoung-Medium-RG.pdf)

![http://ysm-1288cr3g2c.googlecode.com/files/pinouts2.jpg](http://ysm-1288cr3g2c.googlecode.com/files/pinouts2.jpg)

**!!!UPDATE!!!** Anode pins are shown in reverse below. So Pin 20 and Pin 5 are "Seg DP", not "Seg G". And Pin 13 and 12 are "Seg G"
![http://ysm-1288cr3g2c.googlecode.com/files/Pinouts.png](http://ysm-1288cr3g2c.googlecode.com/files/Pinouts.png)

---

# MAX7219/MAX7219 Pins #

As you can see from the above pin-outs of the matrix, almost all of the pins of the MAX will be plugged into to matrix. The only pins you need are 3 digital pins. One for clock, data, and load.

  * The resistor you picked out earlier will connect the I<sub>SET</sub> to Vcc.
  * Your capacitors in parallel will connect between Vcc and the grounds of the MAX
  * The "data" pin from the arduino will connect to the DIN of the first MAX chip. To connect multiple MAX chips, take the DOUT pin to the DIN pin of the next MAX chip.

[Datasheet](http://ysm-1288cr3g2c.googlecode.com/files/COM-09622-MAX7219-MAX7221.pdf)

![http://ysm-1288cr3g2c.googlecode.com/files/MAX.png](http://ysm-1288cr3g2c.googlecode.com/files/MAX.png)

---

# Arduino + Matrix + 2x MAX7221 #

I have the grounds of both chips connecting to the same place because both colors are housed in the same place.

**!!!UPDATE!!!** Pin letters on the matrix are incorrect look at the update note above [Matrix Pins](http://code.google.com/p/ysm-1288cr3g2c/wiki/Step02_Pins_and_Wiring?ts=1361306270&updated=Step02_Pins_and_Wiring#Matrix_Pins)
![http://ysm-1288cr3g2c.googlecode.com/files/Schematic.jpg](http://ysm-1288cr3g2c.googlecode.com/files/Schematic.jpg)

---


**Would you recommend this page?**
> 