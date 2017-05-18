# README #


## Ссылки ##
[wifi-iot.com](https://wifi-iot.com/)
[esptool-gui](https://github.com/Rodmg/esptool-gui)
[esptool](https://github.com/espressif/esptool)


```
#!bash

./esptool.py --port /dev/cu.wchusbserial1420 write_flash -fm=dio -fs=4MB 0x00000 ~/Downloads/0x00000_ESP8266_201705062105.bin

```