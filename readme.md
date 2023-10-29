## Overview

I want to experiment with what my Arduino R4 Wifi board could do, particularly it's dot matrix display. I decide a fun project, would be to implement a dice display. Each time you reset the device it should display a random dice face.

Unfortunately I suspect Arduino's built-in randomiser function isn't quite as random as it should be as seem to see a lot more sixes than I expect. Perhaps there is a way to improve this?

Also it might be interesting to figure out a way to implement some dice games on it, like Yahtzee. At the moment the interface is too simplistic, but perhaps with an additional display and some controller this might be possible. 


### Links

- [Guide to using R4's matrix display](https://docs.arduino.cc/tutorials/uno-r4-wifi/led-matrix)
- [Arduino Matrix editor](https://ledmatrix-editor.arduino.cc/)
- [Arduino lang reference manual](https://www.arduino.cc/reference/en/)
- [Arduino docs on random](https://www.arduino.cc/reference/en/language/functions/random-numbers/random/)
- [Arduino docs on array](https://www.arduino.cc/reference/en/language/variables/data-types/array/)