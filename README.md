# gesture-controlled-leds-opencv-arduino
Real-time hand gesture recognition using Python &amp; OpenCV to control Arduino LEDs through touchless interaction.
✋ Hand Gesture Controlled LED System using Python & Arduino
📌 Overview

This project demonstrates a real-time hand gesture recognition system built using Python (OpenCV) that controls LEDs connected to an Arduino. Hand gestures captured via a webcam are processed using computer vision techniques and translated into control signals sent to the Arduino through serial communication.

The project showcases the practical integration of computer vision + embedded systems, making it ideal for academic projects, portfolios, and research-oriented profiles.

🎯 Key Features

Real-time hand gesture detection

Webcam-based input using OpenCV

Serial communication between Python and Arduino

LED control based on detected gestures

Low-cost, beginner-friendly hardware setup

Modular and easy-to-extend codebase

🛠️ Tech Stack

Software

Python 3.x

OpenCV (cv2)

PySerial

Arduino IDE

Hardware

Arduino Uno / Nano

LEDs

Resistors

USB Cable

Breadboard

Webcam (Laptop camera works)

⚙️ System Architecture

Webcam captures live video

Python processes frames using OpenCV

Hand gestures are detected and classified

Corresponding command is sent to Arduino via Serial

Arduino controls LEDs based on received command

📂 Project Structure
hand-gesture-led-control/
│
├── python/
│   ├── gesture_control.py
│
├── arduino/
│   ├── led_control.ino
│
├── requirements.txt
├── README.md

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/hand-gesture-led-control.git
cd hand-gesture-led-control

2️⃣ Install Required Libraries
pip install opencv-python pyserial

3️⃣ Upload Arduino Code

Open led_control.ino in Arduino IDE

Select correct Board and COM Port

Upload the code

4️⃣ Run Python Script
python gesture_control.py

🖐️ Gesture Mapping (Example)
Gesture	Action
Open Palm	Turn ON LED
Closed Fist	Turn OFF LED
Finger Count	Control multiple LEDs

(Gesture logic can be customized easily)

📸 Output

Live webcam feed

Gesture detection overlay

LEDs respond instantly to hand gestures

🎓 Applications

Touchless control systems

Smart home automation

Human–Computer Interaction (HCI)

Assistive technology

IoT & Embedded Systems learning

🔮 Future Enhancements

Multiple gesture recognition

Wireless communication (Bluetooth / Wi-Fi)

Relay control for appliances

AI-based gesture classification

Mobile camera integration

👤 Author

Hemant Shelar
Electronics & Telecommunication Engineering
Passionate about Embedded Systems, Robotics, and Computer Vision

⭐ Acknowledgment

Special thanks to the open-source community and OpenCV documentation for learning resources.
