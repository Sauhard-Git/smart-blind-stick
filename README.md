# Overview

The Smart Blind Stick is an assistive device designed for visually impaired individuals. It uses an ultrasonic sensor to detect obstacles in front of the user and provides instant audio alerts through a buzzer. This enhances safety and helps users navigate their surroundings more confidently.

---

# Features
Real-time obstacle detection
Audio warning system using buzzer
Simple and cost-effective design
Portable and lightweight
Easy to build and customize

---

# Components Required
Arduino UNO
HC-SR04 Ultrasonic Sensor
Active Buzzer
Jumper Wires
USB Cable
PVC Pipe/Stick
Power Bank or Battery Supply

--- 

How It Works

The ultrasonic sensor continuously emits ultrasonic waves and measures the distance to nearby objects. When an obstacle is detected within a predefined range, the Arduino triggers the buzzer to alert the user. The closer the obstacle, the more immediate the warning.

Circuit Diagram

Connect the components as follows:

Component	Arduino Pin
HC-SR04 VCC	5V
HC-SR04 GND	GND
HC-SR04 Trig	D9
HC-SR04 Echo	D10
Buzzer (+)	D8
Buzzer (-)	GND
Applications
Assistance for visually impaired individuals
Obstacle detection system
Educational Arduino project
Safety navigation aid
Future Enhancements
Water detection sensor
GPS location tracking
GSM emergency notification system
Voice feedback module
Rechargeable battery support
Project Images
![Project Setup](images/blind-stick.jpg)
Demo Video
[Project Demonstration](demo.mp4)
