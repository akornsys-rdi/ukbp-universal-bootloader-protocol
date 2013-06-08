UKBP-universal-bootloader-protocol
==================================

### Universal K Bootloader Protocol for MCUs ###

      _   _ _  _____ ___ 
     | | | | |/ / _ ) _ \
     | |_| | ' <| _ \  _/
      \___/|_|\_\___/_| 

Project developed by [Kwendenarmo](http://kwendenarmo.es/ "kwendenarmo") (<devel@kwendenarmo.es>).  
This project is under GPLv3 licence. See COPYING file.  
See CHANGELOG file to check the history of dates, versions and changes.  
README.md file.

## What is it ##

*UKBP* is a new universal system for loading firmware on microcontrollers. 
Arises from the need of an independent system both the manufacturing and communications module that is to be used. 
It also is designed as routine for greater flexibility and supports a large set of instructions and customizations.

## Features ##

*UKBP* has the following features:

* System designed to be versatile, flexible and robust. Available in two versions (depending on design requirements).
    - Small bootloader. Extends the functionality with an advanced bootloader protocol and design-time advantages.
    - Fail-safe bootloader. This version is safe against possible reboots or communication failures during the firmware update. It can also keep your old firmware.
* The bootloader is structured into independent blocks, giving it more power.
* Extends the life of the flash/eeprom, minimizing the number of writes.
* Deployable on any microcontroller capable of self-writing, regardless of your manufacturer or communications module that have.
* Designed to function as routine can be invoked at program startup or any time during runtime.
* The communications protocol allows encapsulated in other transport layers.
* The bootloader can be reprogrammed himself.
* Allows management of a GPIO to indicate that the boot loader is active.
* The reset and interrupt vectors are fully customizable, directing them to position that the user desires.
* The communication protocol has timeout detection preconfigured to one second.
* Sets the fastest available communication automatically.
* Allows to use in professional and high performance areas.

## Latest version ##

Visit the UKBP main web site for the latest news and downloads:  
<http://devip.kwendenarmo.es/projects/ukbp>  
On this website you will also find all the documentation and development information.

To download the very latest source code, you can do it from GitHub:  
``git clone https://github.com/kwendenarmo/ukbp-universal-bootloader-protocol.git``

## Installation and use ##

See INSTALL file for instructions to follow.

## Known bugs ##

To see the list of known bugs of this software or if you've found one and want to report it, see BUGS file.

