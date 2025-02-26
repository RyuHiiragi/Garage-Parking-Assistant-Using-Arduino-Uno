# Garage Parking Assistant Using Arduino Uno

This repository contains the Arduino code, configuration, and assembly instructions for building a garage parking assistant using an Arduino Uno and an ultrasonic sensor. The system measures the distance between the car and the garage wall, providing visual feedback via LEDs and audible alerts via a buzzer to assist with safe parking <button class="citation-flag" data-index="1">. This project is ideal for improving parking accuracy and preventing accidental collisions in tight spaces.

---

## Table of Contents
1. [Overview](#overview)
2. [Components Used](#components-used)
3. [System Dimensions](#system-dimensions)
4. [Assembly Instructions](#assembly-instructions)
5. [Arduino Code Explanation](#arduino-code-explanation)
6. [Contributing](#contributing)
7. [License](#license)

---

## Overview
The garage parking assistant uses an HC-SR04 ultrasonic sensor to measure the distance between the car and the garage wall. Based on the measured distance, the system provides feedback via LEDs and a buzzer <button class="citation-flag" data-index="6">. A green LED indicates a safe distance, a yellow LED warns the driver to slow down, and a red LED with a buzzer alerts the driver when the car is too close <button class="citation-flag" data-index="8">. This project helps drivers park safely and accurately.

---

## Components Used
To build this garage parking assistant, you will need the following components:
- **Arduino Uno**
- **HC-SR04 Ultrasonic Sensor**
- **Red LED**
- **Yellow LED**
- **Green LED**
- **Active Buzzer**
- **220Ω Resistors**
- **Jumper Wires**
- **Breadboard (Optional)**

---

## System Dimensions
For an ideal garage parking assistant:
- **Height**: 10–15 cm
- **Width**: 10–15 cm
- **Length**: 10–15 cm

These dimensions ensure that the system is compact yet spacious enough to house all components.

---

## Assembly Instructions
Follow these detailed steps to assemble your garage parking assistant:
1. Connect the HC-SR04 ultrasonic sensor to the Arduino Uno for measuring distance.
2. Connect the LEDs and buzzer to provide visual and audible feedback.
3. Optionally, connect a 7-segment display for numerical distance readings.
4. Power the system using a USB cable.
5. Secure all components inside a protective enclosure.

---

## Arduino Code Explanation
The provided Arduino code measures the distance using the ultrasonic sensor and controls the LEDs and buzzer based on predefined distance thresholds <button class="citation-flag" data-index="3">. The system provides real-time feedback to the driver, ensuring safe parking.

---

## Contributing
Feel free to fork this repository and contribute improvements or new features. If you have suggestions or find bugs, please open an issue.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

By following this guide, you should be able to build and test your own garage parking assistant using the Arduino Uno. Happy tinkering! 🚀
