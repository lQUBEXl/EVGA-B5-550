# EVGA-B5-550


Preface: these are not my photos -- provided to me by **Grand#6224** on Discord

## Interior 
Looks to be based off what the EVGA GT is, but more like a custom platform from HEC. DC-DC converters on a modular board with Half Bridge LLC resonsant circuit for stepping down our DC voltage.

![](https://i.imgur.com/0sFbgLb.jpeg)
* Here is the main layout of the unit. From the bottom left, we can see the soldered onto a PCB part of the AC repactacle and beginnings of an EMI filter. We find a CM choke, and X + Y capacitor on the board itself.

![](https://i.imgur.com/Snjf38A.jpeg)
* DC-DC converter coils 

![](https://i.imgur.com/FhFfoW0.jpeg)
* Secondary / output capacitors from Teapo 

![](https://i.imgur.com/JkH6vMP.jpeg)
* Bulk capacitor resonable for smoothing out the voltage ripple from the bridge rectifier. Voltage threshold of 400, 390uF capacitance from Chemi-con rated for 105C operation.

![](https://i.imgur.com/hDZoONj.jpeg)
* Main winding for DC voltage stepdown -- commonly branded by EVGA. 

![](https://i.imgur.com/4ZT3AG1.jpeg)
* Supervisor  IC is a Weltrend WT7527RA that hosts OCP, OVP, UVP, SCP, PG on its 16pin DIP. Needless to say, testing will need to be done to prove that OTP is not only there as EVGA claims, but also functional (as goes for the rest of the unit's protections).

![](https://i.imgur.com/9J7V7Rf.jpg)
* Fan is also used by Cooler Master's MWE Gold V2 1050/1250w [unit](https://www.coolenjoy.net/bbs/review/886445). It is a fluid dynamic bearing from Shenzhen Dongweifeng Electronic Technology.
