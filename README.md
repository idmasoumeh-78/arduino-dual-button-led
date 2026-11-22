# Dual-Button Controlled LED

## Project Overview
This project demonstrates how to use digital input and output on an Arduino Uno R3. The goal is to control the state of an LED using two separate push buttons. To simplify the circuit, the internal pull-up resistors of the Arduino are utilized, eliminating the need for external resistors for the buttons.

## Features
- **in1 (Input):** Turns the LED **ON**.
- **in2 (Input):** Turns the LED **OFF**.
- **Hardware Optimization:** Uses `INPUT_PULLUP` to reduce component count.
- **Debouncing:** Includes a small delay to ensure stable input reading.

## Hardware Requirements
- Arduino Uno R3
- 1x LED
- 2x Push Buttons
- Jumper wires and breadboard


## How it Works
The buttons are connected between the digital pins and the Ground (GND). Since the internal pull-up resistors are enabled, the pins will read `HIGH` when the button is not pressed and `LOW` when the button is pressed.

## Software
The code is written in C++ using the Arduino IDE.
