## Adafruit Sparkle Motion Stick - WLED-friendly USB Stick PCB

<a href="http://www.adafruit.com/products/6332"><img src="assets/6332.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Sparkle Motion Stick - WLED-friendly USB Stick. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6332

### Description

The Adafruit Sparkle Motion Stick is part of our series of "Sparkle Motion" boards, which are our attempt to make the best small WLED-friendly smart LED driving board in the whole world. Our resident mermaid, firepixie makes a lot of projects with WLED, and she loves it! So, how can we make something powerful enough to drive advanced LED projects that need a compact design?

The USB Stick version of the Sparkle Motion is a simpler version of our full-featured Sparkle Motion. It even fits into a low cost off-the-shelf case for protection. Please note the case is not included with this product, so don't forget to pick one up if you want it in a case!

* Power via USB Type A for up to 5V 2A input - you can use off-the-shelf USB battery packs for portable operation.
* 2 Amp resetting fuse to protect from over-current drive
* ESP32 mini module with built-in antenna port - the classic ESP32 has the best WLED support, even if we'd prefer the 'S2 or 'S3. Comes with 4 MB of flash, dual-core 240MHz Tensilica, WiFi, Bluetooth LE, and Bluetooth Classic support.
* USB-serial converter with auto-reset
* Two output signals plus 5V power and ground - both signal outputs are level shifted to 5V.
* Built-in I2S microphone for audio-reactive projects
* Built-in Infrared receiver on GPIO 10 for easy remote control integration
* User button on GPIO 0 which you can press even when its in the snap-on case
* Red built-in LED on pin 4
* Small built-in NeoPixel on pin 18
* Screw terminal blocks for no-solder connectivity

Compared to our larger Sparkle Motion board, this only supports 5V and doesn't have a reset button, there are fewer outputs, and no breakout pads of I2C/GPIO connections for external accessories.
Compared to our Sparkle Motion Mini, this has a USB A port so it's 2A max power. It does have IR and built-in terminal blocks but does not have GPIO breakout pads.

While we recommend it for use with WLED, it will also work just fine as a compact ESP32 board for use with Arduino, ESP-IDF, MicroPython, CircuitPython, or any other ESP32-supported codebase. 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
