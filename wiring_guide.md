WIP

Used Raspberry Pi pins:

03 GPIO02 I2C SDA ->  PN532 SDA
05 GPIO03 I2C SCL ->  PN532 SCL

19 GPIO10 SPI MOSI -> LCD SCREEN and CC1101
21 GPIO09 SPI MISO -> CC1101
23 GPIO11 SPI SCLK -> LCD SCREEN and CC1101

33 GPIO13 PWM1 -> WS2812

27 GPIO00 - -> 5 Buttons Navigation Module (UP)
29 GPIO05 - -> 5 Buttons Navigation Module (DOWN)
31 GPIO06 - -> 5 Buttons Navigation Module (LEFT)
28 GPIO01 - -> 5 Buttons Navigation Module (RIGHT)
36 GPIO16 - -> 5 Buttons Navigation Module (PRESS)

37 GPIO26 - -> Infrared Receiver DATA
22 GPIO25 - -> Infrared Transmitter DATA

04 5V - -> LCD Screen Vcc, PN532, CC1101, WS2812
02 5V - -> Step-Up module Vcc Output

17 3v3 - -> Infrared Receiver Vcc, Infrared Transmitter Vcc
06 GND - -> Step-Up module GND Output
14 GND - -> LCD Screen GND
20 GND - -> PN532 GND
25 GND - ->  CC1101 GND
30 GND - ->  WS2812 GND
34 GND - -> Infrared Receiver GND, Infrared Transmitter GND
39 GND - ->

---

USB BREAKOUT Vcc -> TP4056 Vcc In
USB BREAKOUT GND ->TP4056 GND In
USB BREAKOUT D+ -> Raspberry Pi USB input D+ (soldered)
USB BREAKOUT D- -> Raspberry Pi USB input D- (soldered)
