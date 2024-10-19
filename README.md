Water Level Monitoring System

This project automates water level monitoring and pump control using an ESP8266 and Blynk app.
It provides real-time water level data and motor control to enhance water management for households, industries, or farms.

Features

Real-Time Monitoring: Water levels measured with an ultrasonic sensor and displayed in the Blynk app.
Automated Pump Control: Manage the water pump based on predefined levels.
App Integration: Control the motor via the Blynk app and get live status updates.
LED Indicators: Visual water level indicators with LEDs for easy tracking.

Components

ESP8266 NodeMCU
Ultrasonic Sensor (HC-SR04)
Relay Module (for motor control)
5 LEDs for level indication
Jumper wires and breadboard
Blynk app (iOS/Android)

How It Works

The ultrasonic sensor detects water levels.
Data is sent to the Blynk app for real-time monitoring.
The motor (pump) can be manually or automatically controlled via the app.
LEDs visually represent water levels, and the motor status is updated live.

Installation & Usage

Upload the provided code to the ESP8266.
Connect components as shown in the wiring diagram.
Set up the Blynk app with the project template.
Power up the system and remotely monitor/control water levels.

Future Enhancements

Add an alarm system for critical water levels.
Implement scheduling for automatic pump control.

 __        __        _                _______             _                   _____                     _                 
 \ \      / /__ _ __| |__   ___ _ __  |__   __|           | |                 |  __ \                   (_)                
  \ \ /\ / / _ \ '__| '_ \ / _ \ '__|    | | __ _ _ __ ___| |_ _ __ __ _  ___  | |__) | __ _____  ___   ___ _ __   __ _ ___ 
   \ V  V /  __/ |  | | | |  __/ |       | |/ _` | '__/ __| __| '__/ _` |/ __| |  ___/ '__/ _ \ \/ / | | | | '_ \ / _` / __|
    \_/\_/ \___|_|  |_| |_|\___|_|       |_|\__,_|_|  \__ \__|_|  \__,_|\___| |_|   |_|  \___/\_(_)|_|_|_| .__/ \__,_\___|
                                                                                                             |_|        


