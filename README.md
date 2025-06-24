# 🔥 Firefighting Mobile Robot

 Describe project: This is my invidiual project which is a smart mobile robot capable of detecting fire using computer vision and AI, navigating towards the flame, and extinguishing it. It is designed for fire hazard simulation and educational purposes.
 
 Teamsize: 1 
 
 Person: I programmed to control 2 DC servo motors using PID controller and OpenCV image processing program, in addition I also trained AI data on googlecolab. Besides, I have UART communication between 2 microcontrollers Raspberry and STM32.  

 Hardware: 
  Raspberry Pi 3B
  STM32F103C8T6
  Camera USB2.0
  Driver L298N 
  DC Servo
 

 💡 Features
- 🔍 **Fire Detection via AI**: Uses image processing and a lightweight deep learning model (CNN or YOLO) to detect flames in real time.
- 🎯 **PID-Controlled DC Motors**: Ensures smooth and accurate movement using PID algorithm for motor speed and direction control.
- 🚗 **Autonomous Navigation**: Automatically approaches the fire source using camera feedback and obstacle avoidance sensors.
- 📷 **Camera Module**: Captures live video input for AI-based fire recognition.
- 🧠 **Embedded System**: Built on Raspberry Pi and STM32 microcontroller for real-time processing and control.

 💡Project Purpose & Applications
    🏫 STEM Education: Demonstrates real-world integration of AI, robotics, and control systems.
    🏭 Factories & Industrial Zones: Prototype for autonomous fire response in production environments where early detection and rapid action can prevent costly damage.
    🏢 Office Buildings & Warehouses: Acts as an extra safety layer in closed environments.
    🏠 Smart Homes: Basis for future autonomous fire-prevention assistants.
    🧪 R&D and Prototyping: Serves as a testing platform for more advanced firefighting robots.
  
 🛠️ Technical Used
- Python + OpenCV (for image processing)
- YOLOv5 model (for fire classification)
- C (for STM32 motor control)
- PID Algorithm (for DC motor control)
- Raspberry Pi (as main controller)
- STM32 (as motor driver unit)


