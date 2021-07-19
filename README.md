# EVGA-B5-550


Preface: these are not my photos -- provided to me by **Grand#6224** on Discord

## Interior 
It looks to be on the same platform that the EVGA GT is--HEC is the OEM. DC-DC converters on a modular board with Half Bridge LLC resonsant circuit for stepping down our DC voltage.
![](https://i.imgur.com/0sFbgLb.jpeg)
* Here is the main layout of the unit. From the bottom left, we can see the soldered onto a PCB part of the AC repactacle and beginnings of an EMI filter. We find a CM choke, and X + Y capacitor (very basic) on the board itself.

![](https://i.imgur.com/Snjf38A.jpeg)
* DC-DC converter coils 

![](https://i.imgur.com/FhFfoW0.jpeg)
* Secondary / output capacitors from Teapo 

![](https://i.imgur.com/JkH6vMP.jpeg)
* Bulk capacitor resonable for smoothing out the voltage ripple frmo the bridge rectifier. Voltage threshold of 400, 390uF capacitance from Chemi-con rated for 105C operation.

![](https://i.imgur.com/hDZoONj.jpeg)
* Main winding for DC voltage stepdown -- commonly branded by EVGA. 

![](https://i.imgur.com/4ZT3AG1.jpeg)
* Supervisor  IC is a Weltrend WT7527RA that hosts OCP, OVP, UVP, SCP, PG on its 16pin DIP.

## Notes

