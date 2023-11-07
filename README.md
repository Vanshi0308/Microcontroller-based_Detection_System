# Microncontroller-based Detection System

#### By Vanshika Sinha

## Objective

Design a microcontroller-based detection system for a proximity sensor with a neat circuit diagram.

## Components Used

- ATtiny85
- IR Sensor
- LED
- Resistor
- Breadboard
- Jumper wires

## Working of the circuit

The IR LED is connected in forward bias in the sensor module. The LED starts emitting radiations when the battery is switched on and the photodiode detects the reflected radiations, whose output goes to the inverting input of LM393 comparator IC. When the IR detector receives reflected radiations, its resistance drops and the output comparator turns to LOW. The ATtiny85 detects the digital input from the IR module and the LED starts blinking based on the HIGH or LOW logical signal from the IR module.
