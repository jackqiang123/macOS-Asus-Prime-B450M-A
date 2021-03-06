# macOS-B450M-A
macOS Big Sur for Asus Prime B450M-A (OpenCore)

<p align="center">
	<img src="https://github.com/jackqiang123/macOS-Asus-Prime-B450M-A/blob/main/info.png"/>
</p>

Tested with macOS Big Sur 11.6 with OpenCore 0.6.3

## System specification

* **Motherboard:** ASUS PRIME B450M-A
	* Network: Realtek 8111H
	* Audio: Realtek ALC887

* **CPU:** AMD Ryzen 5 2600
* **GPU:** AMD RX580
* **RAM:** crucial DDR4 16GB 2666MHz 


## Known issues

* Memory frequency error value. I am seeing half frequency (1333MHz) in about My Mac. Fix is to update the config.plist to 1) Add Memory field [instruction] (https://dortania.github.io/OpenCore-Post-Install/universal/memory.html) 2) Enable PlatformInfo/CustomMemory to be YES

## Links

* https://github.com/acidanthera/OpenCorePkg
* https://github.com/corpnewt/SSDTTime

## Useful links

* https://github.com/corpnewt/ProperTree
* https://github.com/AMD-OSX/AMD_Vanilla/tree/opencore/17h
* https://opencore.slowgeek.com
