---
layout: default
title: Pi Installation
parent: The Apollo Control Board
nav_order: 3
---
<h2>Pi installation</h2>
<p>The Prometheus MSLA controller board ( APOLLO ) is a carrier board for the raspberry pi 4B.<br>
The communication and power transfer for the pi is made via spring pins ( pogo pins ). They<br>
connect to pads under the pi for a seamless interface. The pogo pins are very fragile and precise<br>
components so some of the pads on the pi need to be modified for a good connection, and to<br>
reduce the risk of breaking them.</p>

<h3>Step1</h3>
<p>With a good pair of flush cutters, cut the first 3 pins of the GPIO pins as flush as possible.<br>
These pins are #2 - 4 - 6 (5V - 5V - GND )</p>

![](./images/CuttingPiPins.jpg)

<h3>Step2 (optional)</h3>
<p>With a small file or a soldering iron smooth the surface of these cut pins so the<br>
pogo pins can have better contact on the pads.</p>

![](./images/finishedPads.jpg)

<p>It should look something like this.</p>

<h3>Step3</h3>
<p>With a sharp point or a soldering iron, scrape or heat the contact test pads. This<br> 
procedure will ensure to remove any potential oxide layer that can prevent the pogo pins from<br>
having a good connection to the pi.<br>
<span style="color: red"><b>*The important pads are ( TP17, TP10, TP6 )</b></span></p>

![](./images/USBPads1.jpg)
![](./images/USBPads2.jpg)

<h3>Step4</h3>
<p>You can now carefully install the pi on the board using the 4 M2.5 screws.<br>
Don’t over tighten the screws to prevent crushing the pogo pins (look at them while screwing).<br>
<span style="color: red"><b>* We strongly suggest installing a proper heatsink on your pi.</b></span></p>

![](./images/ApolloControlBoardTopViewWithPi.jpg)
