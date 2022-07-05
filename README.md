## Adafruit ESP32-S3 TFT Feather PCB

<a href="http://www.adafruit.com/products/5483"><img src="assets/5483.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit ESP32-S3 TFT Feather. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5483

### Description

We've got a new machine here at Adafruit, it can uncover your deepest desires. Don't believe me? I'll turn it on right now to prove it to you! What, you want your very own soft serve ice cream machine? OK well, that's not something we can provide. But we can provide your second-deepest desire: an ESP32-S3 Feather board with a built in IPS TFT color display. It's got all the ~~delicious creamy goodness~~ features of a Feather main board, the comforting warmth of an ESP32-S3 WiFi+BLE microcontroller, and the crispness of a 240x135 pixel color TFT display. All that and it will even plug in nicely into a breadboard, terminal block wing, or Feather Doubler or even just stack on top of another wing.

This Feather comes with native USB and 4 MB Flash + 2 MB of PSRAM, so it is perfect for use with CircuitPython or Arduino with low-cost WiFi. Native USB means it can act like a keyboard or a disk drive. WiFi means it's awesome for IoT projects. And Feather means it works with the large community of Feather Wings for expandability.

The ESP32-S3 is a highly-integrated, low-power, 2.4 GHz Wi-Fi/BLE System-on-Chip (SoC) solution that has built-in native USB as well as some other interesting new technologies like Time of Flight distance measurements and AI acceleration. With its state-of-the-art power and RF performance, this SoC is an ideal choice for a wide variety of application scenarios relating to the Internet of Things (IoT), wearable electronics, and smart homes.

The Feather ESP32-S3 has a dual-core 240 MHz chip, so it is comparable to ESP32's dual-core. However, there is no Bluetooth Classic support, only Bluetooth LE. This chip is a great step up from the earlier ESP32-S2! This ESP32-S3 mini-module we are using on the Feather comes with 4 MB flash and 2 MB PSRAM, as well as lots of 512KB of SRAM so it's perfect for use with CircuitPython support or any time massive buffers are needed: for fast memory access use SRAM, for slower-but-roomier access use PSRAM. It's also great for use in ESP-IDF or with Arduino support.

The color TFT is connected to the SPI pins and uses additional pins for control that are not exposed to the breakout pads. It's the same display as you see here, with 240x135 pixels and is IPS so you get bright color at any angle. The backlight is also connected to a separate pin so you can PWM the backlight up and down as desired.

For low power usages, the Feather has a second low-dropout 3.3V regulator. The regulator is controlled with a GPIO pin on the enable line and can shut off power to the Stemma QT port and TFT. There is also a separate power pin for the NeoPixel that can be used to disable it for even lower quiescent power. With everything off and in deep sleep mode, the TFT feather uses about 100uA of current.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
