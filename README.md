# Installation-Script

## Preliminary

* Install readline library and development library:

  ```bash
  sudo apt-get install libreadline${libreadVersion} libreadline-dev
  ```
  
## Installation

The installation script installs EPICS Base and the modules Asyn, StreamDevice and Autosave. The script is tested with Debian 10+, Ubuntu 18+ and Raspberry Pi OS. On the RaspberryPi the module devgpio will be installed additionally. 

The script is configurable to a certain extent. A description will follow soon.
