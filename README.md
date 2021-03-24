# NOTE
This repository is unstable. Until I add basic stable support (full support for G0/1, G92, G90/91, bed, chamber, and nozzle heating) for all Makerbot Gen5 Printers, please use with caution. I am not responsible for any broken printers, but do feel free to [make an issue](https://github.com/sckunkle/mbotmake/issues) with what happened.

# mbotmake
A gcode to .makerbot (Gen 5+) conversion tool, compatable with marlin gcode.

# HOW TO USE 
## Mac/Linux
Install Python 3.8 by your preferred means, then run the mbotmake file in the root of this repository with the files you want to process.
## Windows
Download the exe from [here](https://github.com/sckunkle/mbotmake/releases) and drag and drop your gcode onto the executable.

# PLANNED FEATURES

* Create a Ultimaker Cura plugin
* Add M600 (filament change) support
* Refactor the script into readable code
* Add working PursaSlicer config
* Add makerbot slice ending wipe

# REPORTING BUGS
Please supply a copy of your printer config, the generated .makerbot file, the gcode from your slicer, the makerbot you're using, and a detailed description of the bug you're experiencing. 

# CURRENTLY SUPPORTED PRINTERS
If you have a makerbot that use .makerbot files that isn't in this list, contact me at aidanzcase@gmail.com so that I can test how to properly convert to the printer specifications. 

* Makerbot Replicator Generation 5
