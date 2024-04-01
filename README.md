# RaspAP 240x240 display

The script is the [stats.py](https://github.com/RaspAP/raspap-webgui/blob/master/app/pitft/stats.py) from [@billz](https://github.com/billz) for [RaspAP](https://github.com/RaspAP).
I have adapted it so that it displays the values from [stats.py](https://github.com/RaspAP/raspap-webgui/blob/master/app/pitft/stats.py) but on the display size of 240x240.


## Hardware
I bought a [1.3 inch display from AliExpress](https://aliexpress.com/item/1005001746881831.html). It is identical to the display from adafruit.
Here are a few technical values

| Feature      | Value                   |
|--------------|-------------------------|
| Voltage      | 3.3 v                   |
| Interface    | SPI                     |
| Driver       | st7789                  |
| Color        | full color              |
| TFT size     | 1.3" diagonal           |
| Dimensions   | 38.4mm x 30.8mm x 15mm  |
| Model number | Pi TFT1.3 inch v1.0     |


## Installation
1. install the display on the Raspberry Pi
2. install the display on your Raspberry Pi Activate SPI interface in Raspi-config. [^1]
3. perform the installation steps of the Python Setup RGB Display Library from adafruit [^2]

In the RasAP wiki there were also instructions for the 135x240 [^3] diesplay size, if you have any difficulties you can also have a look there.

[^1]: https://www.raspberrypi-spy.co.uk/2014/08/enabling-the-spi-interface-on-the-raspberry-pi/
[^2]: https://learn.adafruit.com/adafruit-mini-pitft-135x240-color-tft-add-on-for-raspberry-pi/python-setup
[^3]: https://github.com/RaspAP/raspap-webgui/wiki/Mini-PiTFT-stats-display/048299c05532544c9b202fd2f785865541634d01
