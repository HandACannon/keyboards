# Scotto36

A 36 key handwired ortholinear ergo keyboard. Featuring an OLED display with Bongo Cat.

![Scotto36](https://user-images.githubusercontent.com/8194147/191559764-12b65543-1ca8-4dc2-a64d-7f86911f9ffd.jpg)
![Matrix](https://user-images.githubusercontent.com/8194147/191559971-9f1b0120-8619-4255-9f1e-28dc2444472d.jpg)
![Controller](https://user-images.githubusercontent.com/8194147/191560489-4e630d53-32f9-4454-8af2-f948c1dc0cc4.jpg)

# Parts

-   1x - [Arduino Pro Micro (Atmega32U4)](https://amzn.to/3LwgAUq)
-   1x - [0.91" 128x32 OLED](https://amzn.to/3faLsxX)
-   36x - [1N4148 Diode](https://amzn.to/3DMbQZ5)
-   14x - [8mm M2 Spacer](https://amzn.to/3r1xdxO)
-   28x - [M2x6mm Screw](https://amzn.to/3r1xdxO)
-   36x - MX Switches

# Pins

Top left to right. Pins refer to the number on the Pro Micro, for more info see [info.json](QMK/info.json).

-   **Rows** - 15, 14, 16, 10
-   **Columns** - 4, 5, 6, 7, 8, 9, A3, A2, A1, A0

# OLED

Simply wire the OLED pins to the I2C pins on the Pro Micro.

-   SDA -> 2
-   SCK -> 3
-   VCC -> VCC
-   GND -> GND

# Case

The controller is simply hot glued into the bottom of the case.

-   [Plate](Case/Scotto36%20-%20Plate.stl)
-   [Case](Case/Scotto36%20-%20Case.stl)

# Flashing

1. [Install QMK locally](https://github.com/qmk/qmk_firmware)
2. Make changes to the keymap if required.
3. Run `qmk flash -kb handwired/jscotto/scotto36 -km default -c`.

# License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/joe-scotto/keyboards/tree/main/Scotto36">Scotto36</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/joe-scotto">Joe Scotto</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0
