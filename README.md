<img align="right" width="180" alt="Z2300 Doctor" src="misc/logo_z2300doctor/logo.png"/>

## Saving my Logitech Z-2300 stereo

> Because the climate and the biosphere don’t care about our politics and our empty words for a single second. They only care about what we actually do.
> 
> -- <cite>Greta Thunberg, 2020</cite>

I bought a stereo, specifically the [Logitech Z2300](https://productz.com/de/logitech-z-2300/p/nxxLn) a few years ago and loved it.
Unfortunately, the volume knob is making use of an analog potentiometer.
And as you may have guessed - it failed!

But I don't want to scrap it, as I affirm the [Right to Repair](https://repair.eu/) and want to save some money as well as ressources.
Hence, this project was born...

## Situation

The stereo consists of ~~three~~ four main components:
1. 2 speaker to sit on the desk
2. a subwoofer
3. a control satellite to sit on your desk
4. the power amplifier inside the subwoofer

As part of this project, I need a new control satellite.
As the current tendency is to clean up your desk, I don't want any additional hardware sitting on my desk.
Hence, controlling the volume is done from my pc, resulting in a less complex PCB and also overcoming conflicts with the original design.

In further designs, I may include a MCU for additional functions, such as Bluetooth or ADC for light control of e.g. LED strips, dependent on the volume.
If you feel like going forward to it, feel free to fork!

## Overview

* [PCB](pcb/): Contains the [KiCad](https://www.kicad.org/) project as well as Gerber Data and the BOM

## License

This project is licensed under the `MIT` License.
`CERN OHL` was also thought of, but I'm not aware of every detail of the license.
I'll try to comply to the [reuse](https://reuse.software/) strategy in later stages of the project.