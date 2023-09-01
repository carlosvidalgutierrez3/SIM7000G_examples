# Example code from TinyGSM for LILYGO T-SIM7000G
It consists of three examples by [TinyGSM](https://github.com/vshymanskyy/TinyGSM/tree/master#getting-started), adapted to work with the LILYGO board. Two for Arduino IDE and one for Platformio.
Just write in your APN and it should be good to go.

When using Arduino IDE, install first the TinyGSM library. (Go to *Tools > Manage Libraries...* and search *TinyGSM* by vshymanskyy).

Sometimes you might mess up with the modem, you need to execute the [*ResetModem.ino*](https://github.com/Xinyuan-LilyGO/LilyGO-T-SIM7000G/tree/master/examples/Arduino_TinyGSM) code provided by LILYGO.

I have also found that sometimes flashing the code [*Arduino_NetworkTest*](https://github.com/Xinyuan-LilyGO/LilyGO-T-SIM7000G/tree/master/examples/Arduino_NetworkTest) can also "reset" the board and make it work again. 

## Hardware
[LILYGO T-SIM7000G](https://github.com/Xinyuan-LilyGO/LilyGO-T-SIM7000G)