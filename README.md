# VitaUSB
A Ps vita usb adaptor for the vita based on yifanfu's schematics here: https://github.com/yifanlu/psvsd (he was a massive help with questions and looking over it for me).

# OSH Park link 
3g: https://oshpark.com/shared_projects/GDik3kMx 
wifi: https://oshpark.com/shared_projects/Ndr1LAlX

be warned they dont provide the correct thickness of 1mm 

Circuit:
3g Version (requires no soldering to the vita):

![circuit](http://i.imgur.com/ug2KuRa.png)

Wifi Version (requires soldering to the vita with 4 wires):

![circuit](http://i.imgur.com/YdT3wTu.png)

For the wifi version you will manually have to wire it up to the board yifanlu's schematic of the mpcie connector will help here (https://github.com/yifanlu/psvsd/blob/master/breakout/breakout.sch)

# Chip:

MCP1640 (6 pin variant) the chip is a boost converter as the vita outputs 4.2V this will increase it to 5v

# WARNING
As of this moment i have not tested the board i do not know if it works or not although in theory it should.
