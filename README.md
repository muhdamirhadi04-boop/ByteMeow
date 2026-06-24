# ByteMeow: Intelligent Cat Food Dispenser
## Project Overview
ByteMeow is an IoT-based smart cat food dispenser that optimizes pet care while maximizing energy efficiency. Unlike traditional timed feeders, this system significantly reduces electricity consumption by automatically activating its dispensing actuators based on feline motion detection and surrounding environmental conditions. By combining IoT technology with smart power management, the device ensures precise feeding, prevents food staleness, and minimizes standby power drain.
## Sensors
 1. DHT11 Humidity & Temperature Sensor – Monitors the air humidity and temperature 
 2. HC-SR04 Ultrasonic Sensor – Detects the presence of an object 
 3. LDR (Light Dependent Resistor) Sensor – Detects ambient light exposure 
 4. MQ-Series Gas Sensor – Monitors the odor
 ## Actuators
 1. Buzzer – Sounds a rhythmic alarm at 2-second intervals when high humidity (\ge 50\%) is detected inside the main food container.
 2. Servo Motor – Rotates to open the food dispenser flap for 5 seconds when an object is detected within 5cm of the ultrasonic sensor, then closes it.
 3. Traffic Light LED Module (Red, Yellow, Green) – Visually displays the air quality and odor status based on safe, mid, or dangerous gas levels.
 4. LED Lamp – Automatically lights up and illuminates the container/feeding area when the LDR sensor detects dark conditions.

## Features
1. Monitors the air humidity and temperature inside the main food storage container to prevent the kibbles from getting stale or spoiled.
2. Detects the presence of an object or food level within a 5cm range in the food bowl area.
3. Detects ambient light exposure to determine whether the surrounding environment is bright or dark.
4. Monitors the odor/gas levels around the feeding area to detect waste or bad smell.
## Hardware
1. ESP32 Development Board (Main Microcontroller)
 2. DHT11 Humidity & Temperature Sensor
 3. HC-SR04 Ultrasonic Sensor
 4. LDR Light Sensor
 5. MQ-Series Gas Sensor
 6. Servo Motor (SG90 / MG996R)
 7. Traffic Light LED Module (Common Cathode)
 8. LED Lamp
 9. Buzzer
 10. Breadboard & Jumper Wires
## IoT Platform
1. Blynk
## Team Members
1. Ahmad Faez Danish
2. Muhammad Akmal Haikal
3. Pang Wei Han
4. Muhammad Amir Hadi
