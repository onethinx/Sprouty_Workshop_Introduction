# Workshop 18th of May 2023

## Prerequisites
### Hardware
1. Moisture Sensor (FarmBug)
1. Programmer + cable + adapter PCB

![FarmBug, cable and programmer](https://github.com/onethinx/Workshop_18May2023/blob/main/FarmBug%20&%20programmer.jpeg?raw=true)

### Software for chip setup
The PSoC6 microcontroller on the OTX-18 can be freely configured with PSoC Creator
1. Download PSoC Creator [from here](https://drive.google.com/drive/folders/17IZQReRqCk6mNGf5SMYcHy2We6gLfeac?usp=share_link)
1. Download PDL 3.1.5 [from the same location](https://drive.google.com/drive/folders/17IZQReRqCk6mNGf5SMYcHy2We6gLfeac?usp=share_link)
1. Install PSoC Creator (after installation, check the bottom checkbox to continue without registration information)
1. Install PDL 3.1.5
1. Run PSoC Creator and set the freshly installed PDL by `TOOLS` -> `OPTIONS` -> `PDL v3 (PSoC6 devices) location:` -> `C:\Program Files (x86)\Cypress\PDL\3.1.5`
1. Close PSoC Creator

### OTX-Maestro
The OTX-18 can be programmed and debugged with OTX-Meaestro (Visual Studio Code based Integrated Development Environment)
1. Install OTX-Meaestro according [the instructions from here](https://github.com/onethinx/OTX-Maestro-Windows)

### FarmBug and programming hardware
1. Make sure the programmer, adapter PCB and cable are connected to the FarmBug as shown:
 ![FarmBug, cable and programmer](https://github.com/onethinx/Workshop_18May2023/blob/main/Connection.jpg?raw=true)
1. Do not install the battery when using the debugger.
