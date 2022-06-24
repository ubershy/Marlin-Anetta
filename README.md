# Anetta

This is the firmware for my Anetta 3D printer (heavily modified Anet A6).  
This firmware is based on bugfix-2.0.x branch of Marlin firmware.  
My personal comments start with "`Litty: `" in the configuration files. 

## Useful Extra Files for Anetta
Located in [0Extras/](/0Extras/) directory.  
<sub><sup>I'm too lazy to create a separate repo for them...</sup></sub>
1. ### Custom 3D Printer Definition for Cura  

    Located in [0Extras/CuraCustomPrinterDefinition/](/0Extras/CuraCustomPrinterDefinition/) along with installation instructions.  

    You want it, because it provides **geometry dimensions** for Anetta, **ABL mesh preload** and **nozzle wipe** features in the "start gcode", also some useful things like **Support Z Distance always equals Layer Height** (can be overriden in quality profile) and **"Elephant foot" compensation for any line width**.  

    Or you can use the information from this definition to create printer definition for any other slicing software.
2. Other files may be added in future

###  [The original Marlin README is here.](https://github.com/MarlinFirmware/Marlin/blob/bugfix-2.0.x/README.md)