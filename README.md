<a href="https://creativecommons.org/licenses/by-nc-nd/4.0/"><img align="right" src="./images/cc-by-nc-nd--300x104.png" /></a>
<br>
<br>
# PedalinoMini™ 4

PedalinoMini™ 4 operates seamlessly with its 4 footswitches, featuring a big 1.9" color display equipped with WiFi, Bluetooth, and USB MIDI capabilities. It is powered through a USB-C port, using either a power adapter or, for enhanced convenience, a compact power bank, ensuring up to 6 hours of uninterrupted functionality.

![](./images/PedalinoMini%204.jpg)

# Bill of Materials

![](./images/PedalinoMini%204%20Naked.jpg)

Quantity|Description|Version|Link|Price (USD)
:------:|-----------|-------|----|-----:
1|PedalinoMini™ 4 [STL files](https://github.com/pedalino-sponsors/PedalinoMini-4)||[Link](https://github.com/sponsors/alf45tar/sponsorships?sponsor=alf45tar&tier_id=378691&preview=false)|9
120 g|3D printed case (minimum size of printing bed 250 mm)|PLA||5
1|T-Display-S3|Soldered Pin [H577]|[Link](https://www.lilygo.cc/products/t-display-s3?variant=42351558590645)|15
1|T-Display TF Shield|Female Pin [H610]|[Link](https://www.lilygo.cc/products/t-display-tf-shied?variant=42729797025973)|3
4|SPST Momentary Soft Touch Foot Switch|||8
7 leds|WS2812B 5050 RGB LED Strip|5V 30 led/m IP30||1
2 m|Wire AWG24|AWG24||1
2|M3 Hex Socket Cap Screw 8 mm|M3x8||0.2
4|M3 Hex Socket Cap Screw 10 mm|M3x10||0.4
3|M3 Bolt|||0.3
|||||----------
||||Total|42.90

# Wiring

![](./images/PedalinoMini%204%20Wiring.jpg)

# Exploded View

![](./images/PedalinoMini%204%20Exploded%20View.jpg)

# Slicing Results

![](./images/PedalinoMini%204%20Slicing%20Results.jpg)

# Firmware upload

1. Press and hold the DOWN button, plug the USB-C cable, release the DOWN button
> [!NOTE]
> The ESP32-S3 chip needs to be in bootloader mode for the detection as a DFU device and flashing.

2. Visit http://alf45tar.github.io/PedalinoMini/installer
> [!NOTE]
> Use Google Chrome or Microsoft Edge browser. Safari and iOS devices are not supported yet.

3. Select the latest firmware available
4. Press "Connect via USB"
5. Select the USB/UART port where PedalinoMini™ 4 is connected and press "Connect"
6. Select "INSTALL PEDALINOMINI™", flag "Erase device", press NEXT and press "INSTALL"
7. Wait a couple of minutes to complete the installation and press "NEXT" at the end
8. Disconnect and reconnect the USB-C cable to reboot the device
9. Repeat step 2, 4, 5
10. Select "CONNECT TO WI-FI"
11. Select the Wireless Network, enter the Password of your WiFi and press "CONNECT"
12. Select "VISIT DEVICE" to access web user interface

# Prototype

![](./images/PedalinoMini%204%20Front.jpg)
![](./images/PedalinoMini%204%20Inside.jpg)
![](./images/PedalinoMini%204%20Top.jpg)
