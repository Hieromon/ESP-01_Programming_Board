# ESP-01 Programming board

DIY board that simplify the flash write for the ESP-01 module.


![ESP-01_Programming_Board](https://raw.github.com/wik/Hieromon/ESP-01_Programming_Board/images/ESP-01_Programming_Board_pic01.jpg)

It can be both flash writing and program execution while the connected by USB-Serial with host PC.
ESP8266 will transition to the flash programming state when GPIO0 is the low level at reset. This programming board is equipped RESET button and FLASH button for controlling the flash programming state transition. 

Press and release the RESET button while hold down the FLASH button, ESP8266 will be flash program state. You can operate remains connected to PC with USB serial and ESP8266 could be programming and running without turn off the connection.

You can easily make a it yourself with universal board and few parts.

1. Tact switch 5x5mm 2pcs.
2. 3mm LED
3. 180Ω
4. 10KΩ
5. 47KΩ 2pcs.
6. TLV1117-3.3
7. Ceramic capacitor 0.01μF 2pcs.
8. Ceramic capacitor 10μF 2pcs. (monolithic recommended)
9. 2x4Pin double row female straight pin-header
10. 1x5Pin single row male right angle pin-header
11. PCB Universal board

## Schematic
![schematic](https://github.com/Hieromon/ESP-01_Programming_Board/blob/master/ESP-01_Breakout_Board.sch.pdf)

![ESP-01_Programming_Board](https://raw.github.com/wik/Hieromon/ESP-01_Programming_Board/images/ESP-01_Programming_Board_pic02.jpg)
![ESP-01_Programming_Board](https://raw.github.com/wik/Hieromon/ESP-01_Programming_Board/images/ESP-01_Programming_Board_pic03.jpg)
