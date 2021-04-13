# robotdyn-w5500-arduino-nano

This is a description of how to wire a Robotdyn W5500 module to an arduino nano. 

![](https://user-images.githubusercontent.com/43075793/114510933-8e54f980-9c37-11eb-90af-017696a3020c.png)

Pins 

<table><tbody><tr><td>Arduino physical pin</td><td>Robotdyn w5500</td><td>&nbsp;</td></tr><tr><td>1</td><td>RST</td><td>&nbsp;</td></tr><tr><td>8</td><td>INT</td><td>&nbsp;</td></tr><tr><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr></tbody></table>

Based on the W5500 Ethernet shield from Robotdyn, I followed the same pins to which the shield is connected to the nano. I did however put the MOSI,  MISO and SCK, RST and 5V to the ICSP pins, see below diagram. 

![](https://user-images.githubusercontent.com/43075793/114511598-6619ca80-9c38-11eb-8957-94fb95d8c3b5.png)

![](https://user-images.githubusercontent.com/43075793/114511367-19ce8a80-9c38-11eb-8262-d595594c1f8a.png)
