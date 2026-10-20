# CPU Board for the PDP-11/Hack V2-3

## Introduction

The PDP-11/Hack is a home-brew PDP-11 compatible computer using eurocard sized
PCBs and DIN41612 bus connectors. The PDP-11/Hack uses it's own bus, named QBUS64,
which is heavily based on the real Q-BUS regarding timing and signalling. The major
difference is that the address/data bus uses non-inverted tri-state signal.

## CPU Card

After the first and so far only CPU card built in 2017 various ideas existed for a
new CPU card that fixes all the issues of the first CPU card and added additional
functions. Most notably the new CPU card has the following features

- DCJ11 processor running up to 22MHz
- 2 or 4 Mbyte of RAM, a PDP-11 can have a maximum of 4Mbyte
- power-up configuration with all 16 bits valid
- maintenance register with all 16 bits valid
- BootROM at the standard IO page addresses 173xxx<sub>8</sub> and 165xxx<sub>8</sub>
- Console using a DC319
- Additional SLU using a second DC319
- Line-time clock
- PDP-11/93,94 compatible advanced status register to read and write the DS1315 real-time clock

![Assembled CPU card Version 2-3 for the QBUS64](https://www.5volts.ch/pages/pdp11hack/images/PDP-11-HACK_CPU-V2-3.jpeg)

## Schematic

![Page 1](https://www.5volts.ch/pages/pdp11hack/images/Schematic-CPU-V2-3_1-6.png)

![Page 2](https://www.5volts.ch/pages/pdp11hack/images/Schematic-CPU-V2-3_2-6.png)

![Page 3](https://www.5volts.ch/pages/pdp11hack/images/Schematic-CPU-V2-3_3-6.png)

![Page 4](https://www.5volts.ch/pages/pdp11hack/images/Schematic-CPU-V2-3_4-6.png)

![Page 5](https://www.5volts.ch/pages/pdp11hack/images/Schematic-CPU-V2-3_5-6.png)

![Page 6](https://www.5volts.ch/pages/pdp11hack/images/Schematic-CPU-V2-3_6-6.png)

## Additional Information

For a full description of this and other projects related not only to PDP-11 
see my [Home Page](https://www.5volts.ch/). For a detailed description of the
CPU Card Version 2-3 see [PDP-11/Hack](https://www.5volts.ch/pages/pdp11hack/)
