# Automatic-Motion-Detection-Light-System-using-PIR-Sensor-and-STM32
This project demonstrates an automatic motion detection system using a PIR (Passive Infrared) sensor and an STM32 microcontroller. The system detects human movement based on infrared radiation (body heat) and automatically turns ON an LED (or light). When no motion is detected, the light turns OFF.

This project is useful for security systems, smart lighting, and energy-saving automation applications.

Components Used...

STM32 Microcontroller (e.g., STM32F446RE)
HC-SR501 PIR Motion Detector Sensor Module
LED
220Ω Resistor
Breadboard & jumper wires
Power supply (5V)

Circuit Connections...

Component	STM32 Pin
PIR OUT	PC1
LED +	PC2
PIR VCC	5V
PIR GND	GND
LED GND	GND 

Working Principle..

PIR sensor detects infrared radiation changes caused by human motion.
When motion is detected → output becomes HIGH.
STM32 reads the signal from PC1.
If HIGH → LED turns ON.
If LOW → LED turns OFF.

Algorithm...

Initialize GPIO pins (PC1 input, PC2 output)
Read PIR sensor output continuously
If motion detected → turn ON LED
Else → turn OFF LED
Repeat

Applications..

Automatic room lighting
Security alarm systems
Smart home automation
Energy-saving systems

Conclusion...

This experiment successfully demonstrates how a PIR sensor can be used with STM32 to build a simple motion-based automatic lighting system, improving energy efficiency and automation.
