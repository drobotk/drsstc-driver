# DRSSTC driver

This is a KiCad project of the DRSSTC driver used in my tesla coil.

# Features:
- Single CT input for both clock and overcurrent detection
- Phase lead adjustable with a potentiometer, no need for a tunable inductor
- Adjustable self-oscillation, useful for testing and running a coil at the upper pole frequency
- Traditional / pulse skipping operation selectable with a jumper
- Adjustable UVLO for protecting precious IGBTs
- 74AHC high speed logic, less phase lead needed
- More modern parts than a UD2.7c

# Credits
As with most DRSSTC drivers, this one is based on previous work of many people (Steve Ward, Finn Hammer, Philip Slawinski, Bart Anderson, Eric Goodchild, Gao Guangyan, etc.). The design I took the most inspiration from is [this](https://highvoltageforum.net/index.php?topic=2054.0) project by [Mike](https://highvoltageforum.net/index.php?action=profile;u=1209) on HVF.
