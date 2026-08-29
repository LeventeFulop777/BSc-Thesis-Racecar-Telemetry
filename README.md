# Development of a Telemetry System for a Battery-Powered Race Car

This repository contains my BSc Thesis in Electrical Engineering, completed at the University of Miskolc in 2026.

## Project Overview
The objective of this thesis was to design and implement a complex, dual-function telemetry system for the Electric Racing Miskolc team. The system provides critical real-time data about the vehicle's condition, which is essential in modern motorsport.

## Key Features
* **Onboard Data Logger:** Saves data from the vehicle's FDCAN network to an SD card using the FatFs file system for post-race analysis.
* **Wireless Transmission:** Transmits telemetry data wirelessly in real-time to the pit lane via a Digi XBee 3 radio frequency module.
* **Transmitter Unit:** Based on a high-performance STM32G474 microcontroller, utilizing custom-designed hardware.
* **Receiver Unit:** Built on an ESP8266 microcontroller that runs an embedded web server using its built-in Wi-Fi capability.
* **Hardware & Software:** The hardware was designed using Altium Designer, while the software was developed in the STM32CubeIDE and Arduino IDE environments.

Please review the attached PDF for the full documentation, hardware schematics, and testing results.
