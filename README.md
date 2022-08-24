# ESP8266-TinyML-test

This repository contains a modified version of the EloquentTinyML library for the ESP8266. 

The official release for the library currently only supports Cortex-M and ESP32 microcontrollers. Therefore, this repository was created to expand the compatiability to the ESP8266.

This project was tested on the ESP8266 D1 Mini.

I do not own this library. For the official library, please visit: https://github.com/eloquentarduino/EloquentTinyML

Note: This library does NOT use the latest version of eloquentTinyML.


## How to use this project

Clone this repository:
''' 
git clone https://github.com/epichl25/ESP8266-TinyML-test.git
```

### Arduino IDE
1. Add the test programme to Arduino IDE: Locate the ESP8266-TinyML-test folder => Go to "ESP8266-TinyML-test/src" and open "main.c" with Arduino IDE.

2. Download the ESP8266 board series from Arduino IDE: Tools => Board => Boards Manager => Type 'esp8266' into the search bar and install the latest version by 'ESP8266 community'. 

3. Select the correct ESP8266 board: Tools => ESP8266 => "choose the correct board you have".
Note 1: Check the board's configurations are correct in the Arduino IDE.
Note 2: Remember to check the correct port has been selected.

4. Add the library to Arduino IDE: Go to Sketch => Include Library => Add .ZIP Lirary => Locate the ESP8266-TinyML-test folder => Go to "ESP8266-TinyML-test/lib" => Add "EloquentTinyML-0.0.10MOD.zip".

5. Verify the programme

6. Upload the programme

