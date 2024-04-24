---
title: Details
---
## Apollo Control Board Details
The Apollo motherboard is based on the RP2040 ARM cortex-M0+ microcontroller and it has
been created for 3D printers ( especially mSLA type ). It’s a carrier board for the Raspberry pi 4B
but can carry other types of SBC with adapters ( coming soon ). As is, it can support 3 stepper
motors for multiple axes and 3 limit switches for them. One power mosfet for power hungry
components like led array or heating bed, with the trigger output to activate an SSR or 
something else if needed. Finally 3x2 12vdc PWM compatible outputs for fans and accessories.

![](./images/ApolloControlBoardPinOut.png)