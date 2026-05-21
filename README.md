# Power Bank PSU eXPerience
**Type**: Power Supply | **Status**: Ongoing

A collection of schematics born from the need to power my audio stomp boxes at 9V. It serves as the "gym" where I tested various configurations before moving to the final, standalone projects in the *TankYou* series.

The type of power source leads to classifying this kind of power supply devices (powerbank) as follows:

- the power source is an external DC adapter (stabilized or not), or low-voltage AC adapter, connected to the mains
- the power source is directly the mains, and we need a transformer to reduce the voltage (and, obviously, we need to work with mains hi-voltage!)

Within the prevoius cassifications, it is possible to determine some features that a powerbank PSU device would be nice to have:

- a lot of output lines
- a lot of available current on each output line
- separate grounds for each output line
- separate regulations for each output line
- current limiter on each output line
- load reverse polarity protection
- DC source reverse polarity protection (only if the power source is a DC adapter to the mains)
- a power plug to connect other devices in a daisy chain


## eXPeriences
Below are some design experiences I made to power my audio stomp box and other small 9V devices.<br/>
The 3-digit code used in the names indicates: (isolated grounds) - (lines per ground) - (output voltage).

- powerBANK-149 (alias ["powerBANK 4"](powerbank-4)) - early tests on 4 lines with a common ground.
- powerBANK-149 (alias ["TankYou"](https://github.com/gom9000/TankYou/tree/master)) - final implementation in a compact format.
- powerBANK-229 (alias ["TankYou rev2"](https://github.com/gom9000/TankYou-rev2/tree/master)) - evolution featuring isolated grounds and direct mains connection.


## About & License
**Author**: Alessandro Fraschetti (gom9000).<br/>
**License**: This experience is licensed under the [MIT License](LICENSE). The license applies to all the documentation, schematic files, and PCB layouts provided in this repository.