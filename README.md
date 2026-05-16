# model-railroad-crossing-flasher
A simple, compact, plug-and-play Arduino-based model railway crossing automation with bidirectional train detection, optical sensors, realistic fading signal lights and fail-safe logic.

The code can be tested on an already made Arduino Nano online simulator circuit: [https://wokwi.com/projects/463534180098859009](https://wokwi.com/projects/464211431898620929) 

Model Railway Level Crossing Automation System:

This project simulates a realistic railway level crossing system for H0 or other scale model railways, controlled by an Arduino Nano. The system uses two optical sensors to detect train movement from either direction and automatically activates crossing signal lights.

The warning lights operate with a smooth PWM fade effect, creating a more realistic railway signal appearance instead of abrupt blinking. The logic includes debouncing, direction detection, delayed deactivation, and a safety timeout system to avoid false triggering or permanent activation.

Features:
-Bidirectional train detection
-Automatic crossing activation from either sensor
-Realistic alternating red warning lights with PWM fade effect
-Delayed shutdown after train passage (2 seconds)
-Sensor re-trigger protection
-Debounce filtering for stable detection
-Safety timeout protection (120 seconds)
-Designed for H0 scale railway layouts

Hardware Used:
-Arduino Nano
-Optical IR sensors (phototransistor + IR LED)
-Red signal LEDs
-Current-limiting resistors
-Wiring and 5V power supply

Circuit diagram:

<img width="3000" height="1969" alt="circuit_image" src="https://github.com/user-attachments/assets/74fb87a6-ac3a-4dc0-86a3-e6e18237ed34" />


This project is meant to create a realistic and reliable railway crossing automation system suitable for model railway enthusiasts and educational electronics projects, designed to be a plug-and-play, simple and compact system.


Designed and programmed by Turzai Edward-Marius (RailTech-TRZ).

