# Smart Automatic Medicine Dispenser with IoT Alert System
A smart solution designed to automate medication dispensing and ensure timely intake for elderly or chronically ill patients. It combines real-time hardware control with IoT connectivity to notify users and caregivers, reducing missed doses and enhancing healthcare support.

# Introduction
Medication non-adherence is a major challenge, especially among elderly individuals or those with memory impairments. This project introduces a Smart Automatic Medicine Dispenser that:
-Uses a Real-Time Clock (RTC) to track time
-Activates a servo motor to dispense medication
-Sends real-time IoT alerts via platforms like IFTTT
-Helps patients and caregivers stay informed, reducing human error and improving health outcomes

# Workflow
-RTC Module continuously checks the current time
-At a predefined time, the servo motor rotates 45° to dispense a pill
-After 4 doses (180°), it resets to 0° for the next day
-Upon dispensing, a Wi-Fi-enabled module (ESP8266) sends an alert via IFTTT to the user's mobile device
-The user or caregiver receives notifications like:
-“Dose dispensed at 10:00 AM”
-“Missed dose”

# Features
- Automated time-based dispensing using RTC
- Servo motor control for accurate rotation
- IoT alert system via Wi-Fi and IFTTT webhook
- Mobile notifications sent instantly
- Automatic daily reset mechanism
- User-friendly design targeting elderly users
- Reduces medication errors and enhances adherence

 # Future Work
- Voice Assistant integration (e.g., Alexa, Google Assistant)
- Offline mode for weak network zones
- AI for predicting adherence patterns
- Environmental sensors (temperature/humidity monitoring)
- Mobile app dashboard with dose history & caregiver control

# Technologies Used
-Microcontroller	Arduino / NodeMCU (ESP8266)
-Time Module	RTC DS3231
-Servo Control	Standard SG90 Servo
-Connectivity	Wi-Fi (ESP8266)
-Notifications	IFTTT Webhooks
-IDE	Arduino IDE
-Language	C/C++ (Arduino)

# Devices & Components Used
- Arduino Uno or NodeMCU ESP8266 (for Wi-Fi)
- DS3231 RTC Module
- SG90 Servo Motor
- Wi-Fi network (for IoT alerts)
- Power supply (5V regulated)

# Author
**Harshit Khanna**
