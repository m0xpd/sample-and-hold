# S&H
A Sample and Hold for Eurorack, based on the LF398


<p width=40%, align="center">
<img width=40%, src="https://github.com/m0xpd/sample-and-hold/assets/3152962/3dcf815b-d350-4177-bf48-5fa0a5e17661">
</p>  


This repository describes a simple sample & hold module, developed for electronic synthesisers, in Eurorack format, based on the
[LF398](https://www.ti.com/lit/gpn/lf398-n) device. 

**Functional Description**

S&H is designed to be a simple, "no frills" sample and hold. It just detects a rising edge on the TRIGGER input and samples the 
voltage applied to INPUT at the point of this edge and holds on OUTPUT until the next triggering event. There is a GATE output, 
which is asserted for as long as the TRIGGER signal is high and an internal clock, which generates a trigger stream normalled 
to the edge detection circuits when nothing else is plugged into the TRIGGER input.

**Licensing**

S&H is published under a Creative Commons BY-SA 4.0 [License](https://github.com/m0xpd/encore/blob/main/LICENSE.txt)

**Implementation**

The system is implemented on a single PCB.

The schematic for the system is linked by the graphic below below (click for the full-size schematic):

<p width=100%, align="center">
<img width=75%, src="https://github.com/m0xpd/sample-and-hold/assets/3152962/85960574-cbe4-42e9-840e-8b9645dcefed">
</p>  

**Specifications**

S&H is 6HP wide and extends 30mm behind the front panel (when a standard Eurorack power header is inserted).

S&H draws <9 mA (typically 5mA) from the +12V supply and <6 mA (typically 3mA) from the -12V supply.
