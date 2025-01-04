WIP

- Raspberry Pi

| Pin  | Label          | Function                           |
|------|----------------|------------------------------------|
| 02   | 5V            | Step-Up module Vcc Output          |
| 03   | GPIO02 I2C SDA | PN532 SDA                          |
| 04   | 5V            | LCD Screen Vcc, PN532, CC1101, WS2812 |
| 05   | GPIO03 I2C SCL | PN532 SCL                          |
| 06   | GND           | Step-Up module GND Output          |
| 07   | GPIO04        | LCD screen CS                      |
| 11   | GPIO17        | CC1101 CS                          |
| 14   | GND           | LCD Screen GND                     |
| 15   | GPIO22        | LCD screen DC                      |
| 16   | GPIO23        | LCD screen RES                     |
| 17   | 3v3           | Infrared Receiver Vcc, Infrared Transmitter Vcc |
| 18   | GPIO24        | LCD screen BLK                     |
| 19   | GPIO10 SPI MOSI| LCD screen SDA and CC1101          |
| 20   | GND           | PN532 GND                          |
| 21   | GPIO09 SPI MISO| CC1101                             |
| 22   | GPIO25        | Infrared Transmitter DATA          |
| 23   | GPIO11 SPI SCLK| LCD screen SCL and CC1101          |
| 25   | GND           | CC1101 GND                         |
| 27   | GPIO00        | 5 Buttons Navigation Module (UP)   |
| 28   | GPIO01        | 5 Buttons Navigation Module (RIGHT)|
| 29   | GPIO05        | 5 Buttons Navigation Module (DOWN) |
| 30   | GND           | WS2812 GND                         |
| 31   | GPIO06        | 5 Buttons Navigation Module (LEFT) |
| 33   | GPIO13 PWM1   | WS2812                              |
| 34   | GND           | Infrared Receiver GND, Infrared Transmitter GND |
| 36   | GPIO16        | 5 Buttons Navigation Module (PRESS)|
| 37   | GPIO26        | Infrared Receiver DATA             |

- USB Breakout

| Connection | Function                             |
|------------|-------------------------------------|
| Vcc        | TP4056 Vcc In                       |
| GND        | TP4056 GND In                       |
| D+         | Raspberry Pi USB input D+ (soldered) |
| D-         | Raspberry Pi USB input D- (soldered) |
