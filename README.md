# #lighthack
This repository contains the source and documentation for **#lighthack**, an educational project designed by ETC users and employees to engage with the DIY community.

#lighthack is a community-supported initiative, and your fellow #lighthackers are your first resource for help!

The #lighthack project is centered around Arduino-based hardware devices that users assemble from scratch. The Arduino connects via a USB COM port and then communicates via OSC with ETC's Eos software.

Eos supports this functionality on Win7e-based consoles and ETCnomad for Windows in software version 2.6.1 and newer. ETCnomad for Mac support is targeted for the near future.

_Support for XPe-based consoles or XP computers is not planned for this project. Many XPe-based consoles can be [upgraded to Win7e](http://www.etcconnect.com/Support/Articles/Windows-7-Upgrade-Eligibility.aspx) to make them compatible with #lighthack._

## test tools/usb_test
This is the first Arduino sketch to load - it helps to ensure that the Arduino is communicating successfully with Eos. This is also a good point to return to if you want to re-confirm the Arduino-Eos connection later on.

## #lighthack box 1
**#lighthack box 1** is a kit project with two encoders, three buttons and a 2x20 display. This project is located in the box_1 subfolder. This folder contains an assembly instructions document which is a good jumping-off point. It also contains the Arduino sketch and other supporting documentation.

## About this ETCLabs Project
#lighthack projects are designed to interact with ETC products, but they are not official ETC hardware or software. For challenges using, integrating, compiling, or modifying items in this project, we encourage posting on the [Issues page](https://github.com/ETCLabs/lighthack/issues). Again, #lighthack is a community-supported initiative, and the #lighthacking community is the best place to ask for help!

## Dependencies
Requires the Arduino OSC parsing library maintained by the great folks over at [CNMAT](https://github.com/CNMAT/OSC). The assembly instructions documents contain details on how to add this to your Arduino project.

[Supported OSC Commands](https://github.com/ETCLabs/EosSyncLib/blob/master/Supported%20OSC%20Commands.pdf)
