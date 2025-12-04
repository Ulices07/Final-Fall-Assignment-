# Water Level Sensor 💧

A typical Keyestudio water level sensor (KS0048 comb stysle board) is a small, low cost module that detects prescence and approximate ehight of water by measuring how conductive th water is acrossed exposed metal. 

# How it functions 
A typical Keyestudio water level sensor works by using the conductiivity across exposed copper traces to produce analog voltage that change with immersion dept, which then a microcontroller like an Arduino can read as an analog value. 

# How to use
This module contains 3 pins being, GND, VCC(5v), and an analog singal pin that connects to an analog input of a board such as Arduino. When running the code, it will repeatedly read the analog value and apply thresholds or scaling, for example, turning on an LED if the value exceeds a set point or even map the readings to a percentage water level for display. Low values mean dry or low water contact while higher values mean more of the probe is submerged, allowing you to trigger alarms or control pumps at chose thresholds. 

<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/c727fe5e-acf1-471f-b5cf-24c1e2d37f71" />

[Uploading Video.mov…]()
