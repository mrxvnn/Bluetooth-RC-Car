# Bluetooth-RC-Car
Arduino-based RC car controlled via Bluetooth. Handles forward, backward, left, and right movements, with added lights and horn. Demonstrates skills in embedded systems, motor control, and wireless communication.

**Features**
Forward, backward, left, and right motion
Bluetooth control via Android app
Lights and horn for added functionality
Smooth motor response using PWM

**Hardware & Software**
Arduino UNO
L298N Motor Driver
HC-05 Bluetooth Module
LEDs & Buzzer (for lights and horn)
Android App (MIT App Inventor)
C++ (Arduino IDE)

**How It Works**
Bluetooth commands from the Android app are received by the HC-05 module. Arduino interprets these commands and signals the motor driver for wheel motion, activates LEDs for lights, and triggers the buzzer for the horn.

**Challenges & Solutions**
Smooth turning: Optimized PWM motor control for better maneuverability
Bluetooth lag: Improved command parsing and timing to reduce response delay
Synchronizing lights and horn: Used separate I/O pins and timers to prevent overlap



