# ESP8266 Industrial Message Board

Industrial LED Message Board based on ESP8266 and MAX7219.

## Project Goal

Develop a professional industrial message board for factory communication.

The system allows Production, Maintenance and Quality departments to send messages through a web interface.

Messages are displayed automatically on a MAX7219 LED Matrix.

## Hardware

- ESP8266 NodeMCU V3
- MAX7219 FC-16 (4 Modules / 32x8)
- WiFi
- USB Power

## Software

- Arduino IDE 2.3.10
- ESP8266 Board Package
- MD_Parola
- MD_MAX72XX
- ESP8266WebServer

## Project Structure

```
ESP8266_Industrial_Message_Board
│
├── Journal_Lumineux_SANIPAK.ino
├── config.h
├── display.h
├── display.cpp
├── queue.h
├── queue.cpp
├── web.h
├── web.cpp
└── README.md
```

## Version

Current Version: V1.0

## Author

Project developed by SOUFIANE EL YOUSFI
