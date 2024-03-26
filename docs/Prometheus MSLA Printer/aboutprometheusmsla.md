---
layout: default
title: About Prometheus MSLA
nav_order: 4
has_children: true
has_toc: false
---
<h3>About the Prometheus MSLA printer</h3>
<p>The Prometheus project began in 2020 with the work of the original founders Samuel Boutin and Melissa Belanger (The Contrapposto Shop). At the time there was not a lot of large format 3D printers on the market and none at a affordable price. Especially no open source (fully or in part). Even to this date the Prometheus MSLA project is the only fully open sourse resin printer. The project aimed to create a similar priced machine as the competition with good performance and give the user full control and ownership of their machine. Nothing will be locked, everything is upgradeable, repairable and more !</p>

After a failed kickstarter at the end of 2021 the contrapposto shop team didnt stop the project and took an other direction. Everything was for the best ! A complete redesign of the machine, new electronics and futur plans were on the table. New members for the Prometheus project started to join and contribute for an even better machine !</p>

<h3>Display Specifications</h3>
<p>The base model of the Prometheus MSLA was designed around a 13.6inch 7K monochrome LCD screen. The same screen used in popular machines like the Anycubic M3 MAX. This display is controlled by a Raspberry Pi 4 which can easily handle that resolution in monochrome. Because the Prometheus MSLA is fully open source other screens can be installed by the user for more pixels, different size, dual screen and more ! The only thing you need is a compatible HDMI driver board for your LCD because a lot of other screen (like the ones from Chitu) run on propriatary protocole. To this day we don't have any real solutions or plans to use those displays.</p>

<h3>Frame<h3>
<p>The Prometheus MSLA frame is build with your nice and friendly 2020 aluminum extrusions and joined using blind joints. This approach gives the opportunity to easily build and modify with a very reasonable cost and sturdy construction.</p>

<h3>Control and firmware - Odyssey<h3>
<p>To be considered as fully open source we needed a firmware to go with the machine. Unfortunately the only piece of software available for more "DIY" machines was NanoDLP. This piece of software has been around for quite some time and have a lot of fonctionnalities. The problems we have are first of all, not fully open (so we can not add special fonctionnalities), we encounter a lot of "bugs" (although it becomes better with each update) and finally in our opinion it's not user friendly and requires a lot of work to set up a machine.</p>

That brings us to the fully open os "Odyssey" ! On our custom mother board "Apollo" we are running klipper a user friendly firmware for your 3D printers. Klipper is the base firmware for controlling the printer with all the accessories in conjonction with Odyssey. "Orion" is our front end user interface to bring everything together. We aimed a simple OS with all the features you need and without the ones you don't ! This is still a work in progress but you can still try our lattest version on github.

<h3>Serial numbers</h3>
<p>  2024 orders on the contrapposto store and the authorized suppliers, the Apollo controller board sold will be equiped with a special IC to keep track of the serial numbers. We will also not release the artwork on the board online to keep it our property. This means that we will be abble to verify in the futur the authenticity of the boards. If the board was made and SOLD from by an unauthorized seller by the contrapposto shop, the team keeps the right to only give minimum support. We hope to protect futur authorized sellers and encourage the support of the project !</p>

----
## Next: [The build](../thebuild.md)