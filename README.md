# Oltronix_B602D_Power_Supply

This repository contains a KiCAD PCB project of the original version A Oltronix regulator board in the LABPAC B602D and B603D power supply.

A repair description of the Power Supply is available here: https://baldpenguin.blogspot.com/2025/02/repairing-oltronix-b602d-power-supply.html

A cleaned up pdf version of the schematic is attached to this repository. Note that the pdf schematic contains an error: version B schematic has a short in opamp A30, input 5 and 6. 

Another discrepance is that in my version of the power supply B602D (version A), the diodes CR91-CR92 are connected like Version B schematic.

I've attached the version A and B schematics with the error fixed (the 0-30V and 0-60V jpg files).

Note that when creating the regulator board PCB with same dimensions as the original, extra long pin headers are required for clearance to some of the components on the main board. A modified version of the PCB would be better with a rounded/cut off corner on the side of the pin header connector.

---

## License

This repository contains a redesigned replacement for the regulator board used in the Oltronix power supply.

The original device and schematic are the property of their respective rights holders and are not included under this license.

This project covers only the original work created in this repository, including the PCB layout, modified schematic, BOM, and documentation.

This project is licensed under the CERN-OHL-S v2 (Strongly Reciprocal).

See `LICENSE` file for details.
