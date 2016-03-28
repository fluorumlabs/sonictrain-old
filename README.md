# FluorumLabs / SonicTrain

[![Join the chat at https://gitter.im/fluorumlabs/sonictrain](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/fluorumlabs/sonictrain?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This is the schematics and PCB repository for the second revision of SonicTrain: Hardware analog audio signal chain modules.

Version: 0.1-alpha2

Modules

Module | Revision | Status | Known issues
------ | -------- | ----------- | ------------
M101 Power Supply | B | Tested | Polarity protection diode bridge is getting hot (50ºC) (#24)
M202 Stereo Input | C | Tested |
M303 Stereo Output | C | Tested |
M907 VU Meter | A | |
M913 Dev Adapter | A | |
A111 Fader | A | |
A210 4-Band EQ | A | |
A212 Kill EQ | A | |
A405 Diode Distortion | A | Tested | Diodes should be connected to ground instead of OpAmp (#19), Output gain too low (#20)
A406 4069 Overdrive | A | |
D104 LoFi Delay | A | |
D108 SpinSemi FX | A | |
D709 VS1053 Synth | A | |
