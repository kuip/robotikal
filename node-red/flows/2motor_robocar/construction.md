# Construction

## BOM

* Arduino MEGA 2560
* HC-05 Bluetooth module
* L9110S DC motor driver module
* RC car chassis with 2 motors ~5V each. One for propupulsion and one for steering
* 6 Ni-MH rechargeables with a support

## Pin Setup

* Pins 2, 3, 6, 7 to motor A, B of L9110S
* GND, 5V to the middle pins of L9110S
* Pins 0, 1, GND, 5V to RX, TX, GND, 5V of HC-05

## Setup

1. Configure HC-05 in AT mode.
2. With Arduino IDE load Firmata/StandardFirmataPlus.
3. In Node-Red import the flow with the necessary plugins: Dashboard and Bluetooth.