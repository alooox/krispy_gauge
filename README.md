# Krispy Gauge
A Open Source Digital Circular Customisable Touchscreen Canbus Gauge

This gauge is currently being optimised for Haltech ECU's https://www.haltech.com but could easily be modified for other ECU's by editing the canbus.ino Values

**Parts Only Kits Available Soon**

**Assembeled Gauges Available Soon**

## Hardware

### Essential Components : 

Seeed Studio XIAO CAN Bus Board (MCP2515) https://s.click.aliexpress.com/e/_Dl9nxDh

Seeed Studio XIAO 1.28 Inch Touch Round Display https://s.click.aliexpress.com/e/_DdEk9zZ

Seeed Studio XIAO ESP32 C3 Wifi/Bluetooth https://s.click.aliexpress.com/e/_DDLxWcL

12v to 5v DC Step Down https://www.aliexpress.com/item/1005001629723875.html (Ensure selecting 5V Model)



### Extra Hardware : 

7 Pin Male Header https://s.click.aliexpress.com/e/_DcYtd1t (Select 7P)  

4 Wire Flex Cable 20cm x 4 pins https://s.click.aliexpress.com/e/_DF3jjPN (Select Same Side, 20CM, 4P) 

4 Pin PCB Header https://www.aliexpress.com/item/4000029705975.html 

6 Pin Right Angle Pins https://s.click.aliexpress.com/e/_Dkx5ZRH (Select 2x6 Pin) 

Single Right Angle Pins https://s.click.aliexpress.com/e/_DEGFR75 (Any Selection)

M2 x 6mm Stainless Button Screws https://s.click.aliexpress.com/e/_DFWEuzl (Select M2 x 6mm)

SuperGlue/CA Glue for front Bezel Adhesion 


### 3D Printed Files :
https://github.com/alooox/krispy_gauge/blob/main/STL

Print one of each of the following parts

1x Main Housing (Recomended 0.15mm to 0.2 Layer height, and Buildplate only supports)

1x Front Bezel (Smallest Layer Height Recomended, 0.10mm or below)

1x Bezel Assembily Tool (0.2mm Layer height)

1x Clamp (0.15mm Layer height)

1x End Cap (0.2mm Layer height)

1x Internal Spacer (0.2mm Layer height)

1x Clamp Tool (0.2mm Layer height) 


### PCB Files : 
https://github.com/alooox/krispy_gauge/tree/main/PCB

Technically the gauge could be assembeled without these custom PCB's but it involves soldering several tiny wires between the 3 boards, the PCB itself actus as a structual part of the gauge, linking all the components together and firmly afixing them to the 3D Pritned housing. 

1x Display to Canbus PCB 

1x ECU to Gauge Backplane PCB

I recomend JLCPCB or PCBWay to get these PCB's Produced


## Software

Precompiled Builds for the Krispy Gauge are available here (LINK)

If you wish to compile Krispy Gauge yourself you will require the following Libraries 

MCP CAN : https://github.com/coryjfowler/MCP_CAN_lib
TFT_eSPI : https://github.com/Bodmer/TFT_eSPI
SEED Roudn Display : https://github.com/Seeed-Studio/Seeed_Arduino_RoundDisplay
LVGL : https://github.com/lvgl/lvgl

File Additions
Setup66_Seeed_XIAO_Round.h will need to be placed in TFT_eSPI > User Setups Folder
User_Setup_Select.h will need to be placed in TFT_eSPI



## Thanks and Mentions

A Special thanks to https://github.com/tolunaygul and https://github.com/analoghan for some of the Keypad Emulation Code
And Special thanks to Haltech for making such awesome products



