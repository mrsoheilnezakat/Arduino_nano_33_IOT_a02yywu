# Distance Measurement with a02yyuw and arduino nano 33 IOT
## Introduction
This project involves measuring distance using a02yyuw sensor connected to a arduino nano 33 IOT. fFrom the sensor side, The red wire should be conected to 3.3v GPIO and black wire should be conected to a GND GPIO, green wire which is RX, and the blue wire whic is TX should be connected accordingly to the RX and TX GPIO of the arduino nano 33 IOT as per the [GPIO map](https://store.arduino.cc/en-de/products/arduino-nano-33-iot) should be connected as it is [wire connections](https://github.com/mrsoheilnezakat/Arduino_nano_33_IOT_a02yywu/blob/main_branch/images/connection.jpeg)

### Components Needed
1. aAduino nano 33 IOT
2. a02yyuw Sensor
4. Jumper Wires

### Connect the a02yyuw sensor to the Arduino nano 33 IOT as follows:

1. VCC (a02yyuw) → 3.3V (nano 33)
2. TX (a02yyuw) → PB22 (nano 33)
3. GND (a02yyuw) → GND (nano 33)
4. RX (a02yyuw) → PB23 (nano 33)


### Code:

Use the following MicroPython code to read data from the DHT22 sensor: [cpp code](https://github.com/mrsoheilnezakat/Arduino_nano_33_IOT_a02yywu/blob/main_branch/measurment.cpp)
 
## Steps to Follow

### Set Up the Hardware:

Connect the a02yyuw sensor to the Arduino to the wiring diagram.

[actual setup](https://github.com/mrsoheilnezakat/Arduino_nano_33_IOT_a02yywu/blob/main_branch/images/connection.jpeg)

### starting with arduino nano 33 IOT

1. Connect the arduino wia micro usb oto your workstation
2. Install arduino IDE on your system
3. From tools menu, select *board* and *port*
4. Write your code
5. Verify your code via check-mark button on top to check if there is any error
6. Deploy it on the device, by clicking on right-arrow button
7. From tools menu, open serial manitor to view the output.

