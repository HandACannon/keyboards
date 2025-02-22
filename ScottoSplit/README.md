# ScottoSplit

A 36 key column staggered split keyboard that uses VGA interconnects.

![ScottoSplit](https://user-images.githubusercontent.com/8194147/202559202-b4863dfc-d575-4ca1-bcd2-e82c444308ce.jpg)
![Matrix](https://user-images.githubusercontent.com/8194147/202559028-be147d3e-a38b-4221-a980-c3d87926314e.JPG)
![Controller](https://user-images.githubusercontent.com/8194147/202559112-329efb1d-a69c-4c78-b043-2be4555b7ae2.JPG)


# Parts

-   1x - [Arduino Pro Micro (Atmega32U4)](https://amzn.to/3LwgAUq)
-   36x - [1N4148 Diode](https://amzn.to/3DMbQZ5)
-   18x - [8mm M2 Spacer](https://amzn.to/3r1xdxO)
-   36x - [M2x6mm Screw](https://amzn.to/3r1xdxO)
-   2x - [VGA Connectors](https://amzn.to/3EgstL6)
-   1x - [VGA Cable](https://amzn.to/3UNPhZF)
-   36x - MX Switches
-   36x - 1u Keycaps

# Pins

Top left to right. Pins refer to the number on the Pro Micro, for more info see [info.json](QMK/info.json).

-   **Rows** - 15, 14, 16, 10
-   **Columns** - 3, 4, 5, 6, 7, 8, 9, A3, A2, A1

# Case

The controller is simply hot glued into the bottom of the case.

-   [Plate](Case/ScottoSplit%20-%20Plate.stl)
-   [Case](Case/ScottoSplit%20-%20Case.stl)

# Flashing

1. [Install QMK locally](https://github.com/qmk/qmk_firmware)
2. Make changes to the keymap if required.
3. Run `qmk flash -kb handwired/jscotto/scottosplit -km default -c`.

# License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/joe-scotto/keyboards/tree/main/ScottoSplit">ScottoSplit</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/joe-scotto">Joe Scotto</a> is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0
