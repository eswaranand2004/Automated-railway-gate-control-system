# Automated Railway Gate Control System

An embedded systems project developed as part of my **B.Tech in Electronics and Communication Engineering at VIT Vellore**.

The project uses an **ESP8266 and IR sensors** to detect trains and automatically control a railway gate. It also includes Wi-Fi-based monitoring and an emergency option to control the gate remotely.

## What it does

* Detects an approaching train using IR sensors
* Automatically closes and opens the railway gate
* Uses ESP8266 for control and Wi-Fi connectivity
* Provides gate status through a Blynk/web dashboard
* Uses LEDs and a buzzer for alerts
* Includes an emergency remote override

## Components Used

* ESP8266 / NodeMCU
* IR Sensors
* L293D Motor Driver
* DC Motor
* LEDs
* Buzzer
* Emergency Button
* 12V Power Supply

## Software

* Arduino IDE
* Embedded C
* ESP8266WiFi
* Blynk
* MQTT / HTTP

## My Contribution

I mainly worked on the **hardware side** of the project, including:

* Setting up the ESP8266 and IR sensors
* Connecting the L293D motor driver and DC motor
* Setting up the power supply
* Integrating the emergency button
* Testing the sensor and motor responses

I also worked with my teammate on testing, documentation, and the final implementation.

## Results

The system achieved around **98% train detection accuracy** and an overall reliability of **96.8%** during testing. The gate took approximately **2.6 seconds to close** and **2.55 seconds to open**.

## Future Improvements

* GSM/SMS alerts
* Better train detection sensors
* Solar power and battery backup
* AI-based train arrival prediction
* Integration with railway signalling systems

---

**Built as an academic project at Vellore Institute of Technology.**
