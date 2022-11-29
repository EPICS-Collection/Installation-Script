# Installation-Script

## Preliminary

* Install readline library and development library:

  ```bash
  sudo apt-get install libreadline${libreadVersion} libreadline-dev
  ```
  
## Installation

The installation script installs EPICS Base and the modules Asyn, StreamDevice and Autosave. The script is tested with Debian 10+, Ubuntu 18+ and Raspberry Pi OS. On the RaspberryPi the module devgpio will be installed additionally. 

The script is configurable to a certain extent. A description will follow soon.

## History

* **May 2016**: Creating an installation script based on: 

  <a href=https://gist.github.com/inigoalonso/a77314206b516e94d4aa target="_blank">inigoalonso/setup-epics-ioc-raspbian.sh</a>
 
* **2016 - 2021**: Further development of the script and adaptation to the needs of the MAGIX experiment in Mainz. Updating of the base and module versions.
* **December 2021**: Decoupling of the installation script. The MAGIX-specific code and the self-developed modules are now separated from the script and can be installed later if required. The same applies to the BaseApp. In addition, the script was adapted to EPICS7.
* **November 2022**: Preparing the script for the use at the Paul Scherer Institute as well as for publishing on Github.
