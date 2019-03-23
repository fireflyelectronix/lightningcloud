
# Lightning Cloud Kit
This is the source code for the Lightning Cloud Kit from Firefly Electronix.

![](https://github.com/fireflyelectronix/lightningcloud/blob/master/images/lightningcloud.jpg)

### Steps for programming

1. Setup your Arduino IDE
   Install the Adafruit Neo Pixel Library. You can do this through the Arduino IDE. 
      1. Click on Tools -> Manage Libraries -> Search
          Search for Adafruit NeoPixel
      1. Download the main .ino file from our source code. 
         Adafruit also has many other examples to do different colors. 
      1. Choose the Arudino UNO as your board. The Bantam Board uses the same exact bootloader as the UNO. 

1. Connect the Bantam Board. Use an FTDI adapter like this one here. https://www.microcenter.com/product/486570/ftdi-adapter-usb-controller

    The pinout on the Bantam Board is marked on the PCB. If you would want to power the board through FTDI, you need to solder the jumper on the bottom of the PCB. Otherwise, you can just power with the battery pack provided with the kit. 
