# ScottoCMD

A 40 key handwired ortholinear keyboard with non-ortho bottom row. Featuring a 128x64 OLED display along with a 6.25u spacebar.

![ScottoCMD](https://user-images.githubusercontent.com/8194147/192900299-f6227d48-331e-4243-8184-eb7e63fac02b.jpg)
![Matrix](https://user-images.githubusercontent.com/8194147/192598876-0521d841-e5e0-4e4a-975f-8156c5917028.jpg)
![Controller](https://user-images.githubusercontent.com/8194147/192900307-a9fc8015-165d-48b0-b433-a629eb0b82c7.jpg)

# Parts

-   1x - [USB-C Arduino Pro Micro (Atmega32U4)](https://amzn.to/3UKt0MH)
-   1x - [6.25u Plate Mount Stabilizer](https://amzn.to/3xUEvHz)
-   1x - [0.91" 128x64 OLED](https://amzn.to/3dLG2ZU)
-   40x - [1N4148 Diode](https://amzn.to/3DMbQZ5)
-   21x - [8mm M2 Spacer](https://amzn.to/3r1xdxO)
-   42x - [M2x6mm Screw](https://amzn.to/3r1xdxO)
-   40x - MX Switches
-   40x - Keycaps
    -   36x - 1u
    -   2x - 1.5u
    -   1x - 1.75u
    -   1x - 6.25u

# Pins

Top left to right. Pins refer to the number on the Pro Micro, for more info see [info.json](QMK/info.json).

-   **Rows** - A0, 15, 14, 16, 10
-   **Columns** - TX0, RX1, 4, 5, 6, 7, 8, 9, A3, A2, A1

# OLED

Simply wire the OLED pins to the I2C pins on the Pro Micro.

-   SDA -> 2
-   SCK -> 3
-   VCC -> VCC
-   GND -> GND

# Case

The controller is simply hot glued into the bottom of the case.

**Most printers will be able to print the case, however, you will most likely have to turn off any skirt or brims.**

-   [Plate](Case/ScottoCMD%20-%20Plate.stl)
-   [Case](Case/ScottoCMD%20-%20Case.stl)

# Spacebar

Getting the spacebar mounted properly can be a massive pain in the ass since 3D printed plates are not as precise as laser cut ones. You should start by using all screws arount the space bar and stabilizers then if you encounter binding, slowly loosen or remove them until it moves properly.

# Flashing

1. [Install QMK locally](https://github.com/qmk/qmk_firmware)
2. Make changes to the keymap if required.
3. Run `qmk flash -kb handwired/jscotto/scottocmd -km default -c`.

# License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/joe-scotto/keyboards/tree/main/ScottoCMD">ScottoCMD</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/joe-scotto">Joe Scotto</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0
