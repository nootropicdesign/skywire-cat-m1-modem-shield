# Skywire Shield: Arduino shield for Nimbelink Skywire CAT M1 and NB-IoT modems

This is a design for a simple Arduino shield for Nimbelink Skywire CAT M1 and NB-IoT modems. Nimbelink modems are designed to have compatible pinouts and electrical characteristics, so it is possible to design a carrier board that works for a large variety of modems. The board has a switching power supply that provides 3.8V to the modem. Jumpers can be used to connect the modem's serial RX and TX to the Arduino hardware serial pins or to pins for use with software serial (digital pins 2 and 3).

A standard 6-pin serial header connection is accessible from the bottom of the board. This is because some modem modules come with a very high default serial rate that must be changed before an Arduino can interface with it. For example, the Sequans Monarch modem has a default rate of 921600. Connect with a terminal program on a computer and change this with the command `AT+IPR=19200`.

For a full description of this project, see [this project on the nootropic design Project Lab site](https://nootropicdesign.com/projectlab/2019/04/21/arduino-shield-for-cat-m1-and-nb-iot-modems/).

![Skywire Shield schematic](https://raw.githubusercontent.com/nootropicdesign/skywire-cat-m1-modem-shield/master/SkywireShield_schematic.png)

![Skywire Shield board](https://raw.githubusercontent.com/nootropicdesign/skywire-cat-m1-modem-shield/master/SkywireShield_board.png)
