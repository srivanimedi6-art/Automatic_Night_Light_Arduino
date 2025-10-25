# Automatic_Night_Light_Arduino
Automatic Night Light using Arduino UNO and LDR – sensor-based LED control for home automation.,

## Aim
To design a night light system that automatically turns ON in darkness and OFF in bright light using Arduino UNO and LDR.

## Components
- Arduino UNO
- LED
- 220Ω resistor
- Potentiometer / LDR
- Jumper wires
- Breadboard

## Circuit Connections
- LED anode → 220Ω → Arduino pin 8
- LED cathode → GND
- LDR / Potentiometer left pin → 5V
- LDR / Potentiometer right pin → GND
- LDR / Potentiometer middle pin → A0

## Code
See `AutomaticNightLight.ino`

## Simulation
[Tinkercad Simulation Link](https://www.tinkercad.com/things/9B5JYEZkMD3-automatic-night-light2025?sharecode=UJF6tCG3FhG-PDmxLcjnBrQiDheq4ErwEXDxjNIUNGs)

## Features
- Automatic ON/OFF based on light intensity
- Beginner-friendly Arduino project
