# XTW-3 FLASH/EEPROM Programmer Notes

The XTW-3 is an inexpensive SPI FLASH and EEPROM programmer.

## Installation

The software for the XTW-3 can be downloaded from the manufacturer site at [http://www.yaojiedianzi.com](http://www.yaojiedianzi.com/index.php?m=Product&a=show&id=16). Look for the small archive icon. The link text is not highlighted in any way.

![XTW-3-download](https://user-images.githubusercontent.com/1106057/153180311-eaa59628-a7f2-4c65-88e1-f1afc6d116ec.png)

Extract the .zip file, and launch `XTW-3.exe`. The application will appear question marks in place of text unless you have the appropriate system languages installed:

![Initial-Screen](https://user-images.githubusercontent.com/1106057/153180574-19c82485-e602-4656-b8df-5d31a874da15.png)

Switch the language to English:

![Switch-Language](https://user-images.githubusercontent.com/1106057/153180590-69ec5930-aa86-4f33-b3c2-6a76f99f8edc.png)

The user interface will display in English, but I found some messages in the status window did not.

![English-display](https://user-images.githubusercontent.com/1106057/153180822-dc4894c0-2673-4742-af05-c8ebe7ec2f7b.png)

Plug your XTW-3 device into a USB port. It The will appear as a _USB Mass Storage Device_, and have a drive letter mapped to it in _Windows Explorer_.

![Device-in-explorer](https://user-images.githubusercontent.com/1106057/153181101-a082d17f-6ac7-4f15-ba2e-cf4c71351d11.png)

The device status in the bottom left corner of the XTW-3 application will also change from _Device offline_ to _Device online_.

![Device-online](https://user-images.githubusercontent.com/1106057/153181315-03061609-e424-409c-8052-084138017e70.png)

## Usage Notes

* The _Detect_ function only works with SPI FLASH chips. You must manually select EEPROM chips because the ID will not be recognized automatically.
