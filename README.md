# Logic probe
**Three state logic probe**

This is a NAND based three state logic probe with an optional buzzer.

The three states are : 
* HIGH         --  Green LED
* LOW          --  Red LED
* UNDETERMINED --  Blue LED

The undetermined step is active when the probe can't figure out if the signal probed is high or low (floating), or when the signal is switching quickly between the two (PWM).
The ".sch"(schematics) and ".brd"(board layout) files are in **Autodesk Eagle 8.0** format.

The PCB can be made of a single sided copper board. Components packages are 1206, 0805, SO14 and SOT23-3.
