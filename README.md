# DIY IoT (in secure way)

# Hardware

ESP8266 based boards/swithes are really attractive to use because of the price/easeofuse/capability ratio. I am using Itead  manufactured Sonoff branded switches together with Arduino and \*pi type (Raspberry, Orange, Banana or other fruit(s)) of microcomputers with both ESP8266 based and nRF24L01 (slightly better coverage, slightly lower power consumption, does not need WiFi base station) based communication modules.

# Software

In the ESP8266 I am using [One of many custom Sonoff firmwares](https://github.com/arendst/Sonoff-Tasmota). I have chosen this one mostly because of the good enough documentation and walkthroughs.
For communication excellent Mosquitto package is installed on \*pi type microcomputer and virtual machine in the hosting.

# Setup

Mosquitto as the bridge from internal network
