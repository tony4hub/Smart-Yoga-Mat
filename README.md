Smart Yoga Mat – Project Documentation
🧘 Overview

This project is an IoT-based Smart Yoga Mat designed to assist users in practicing yoga effectively by providing real-time posture correction, health monitoring, and guided sessions. Using advanced sensors, microcontroller boards, and machine learning techniques, the Smart Yoga Mat helps users track their body movements, heart rate, and temperature, ensuring safe and efficient workouts.



⚙ Features

✔ Real-time posture detection using sensor data
✔ Heart rate and pulse monitoring with MAX30102
✔ Body temperature sensing through MLX90614
✔ Visual feedback on OLED display
✔ Guided yoga sessions through a companion app
✔ Freestyle mode for customized workouts
✔ User-friendly interface and easy hardware setup
✔ Portable and lightweight design with cushioned surface



🛠 Hardware Used

ESP32-S3 Sense – Microcontroller for processing data and connecting with the app

MLX90614 – Infrared temperature sensor for body temperature readings

MAX30102 – Heart rate and pulse oximeter sensor

0.96-inch OLED Display – For real-time feedback

Piezoelectric Sensors & Elements – Step detection and triggers

Vibration Motor – Alerts and haptic feedback

Solar Panel (Backup) – Sustainable energy source

Yoga Mat – Comfortable base for practice



📱 Software Architecture

Data collection from sensors → processed by ESP32.

Feedback loop via OLED and mobile app

ML model integration for posture correction

Wireless communication via Bluetooth/Wi-Fi

User profiles and session history are  stored locally



📈 Challenges Faced

Accurate sensor calibration for posture correction

Ensuring low-power operation while maintaining responsiveness

Integrating ML models within hardware constraints

Handling wireless connectivity without data loss



📌 Future Improvements

Add more sensors for advanced pose detection.

Include voice-guided meditation

Support for multiple user profiles

Integration with cloud storage for data backup
