# PCB

This folder contains details of the PCB for the S&H module:

The PCB design files are presented in Eagle format.

Below you see a photo of the unpopulated PCB, top and bottom side

<p width=100%, align="center">
<img width=40%, src="https://github.com/m0xpd/sample-and-hold/assets/3152962/ed1ce3bc-f91e-45d1-b338-513b30602ff9">
</p>  

## BoM and Capacitor Types

A Bill of Materials is available (in the verbose and not very useful style produced by Eagle.

The important things to note are that:
1) the jack sockets and the sample interval potentiometer are mechanically as well as electrically important; they 
control the spacing between the PCB and the front panel. For this reason, [Thonkiconn](https://www.thonk.co.uk/shop/thonkiconn/) sockets
and [alpha 9mm vertical potentiometers](https://www.thonk.co.uk/shop/alpha-9mm-pots-vertical-t18/) are specified.
2) Capacitor Types are as follows:
   C1 & C2 are polarised electrolytics
   C9 was chosen as a box polyester film (for space) - other types (such as multi-layer polyester) are suitable
   C7 must be a low leakage type - I have used a box polyester film csuccesfully, but (e.g.) polystyrene will also work
   ALL OTHER CAPS ARE CERAMICS

The populated PBC is seen from the component side in the photo below:

<p width=100%, align="center">
<img width=40%, src="https://github.com/m0xpd/sample-and-hold/assets/3152962/8a3a4eac-9338-4db8-95d0-596bd2c8f82b">
</p>  
