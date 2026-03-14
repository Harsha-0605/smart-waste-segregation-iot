----------SMART WASTE SEGRSEGREGATION SYSTEM ♻️----------

An IoT-based Smart Waste Segregation System that automatically detects waste using sensors and directs it into the appropriate bin using a stepper motor controlled
by an A4988 driver.The system also includes a servo motor lid mechanism and environmental monitoring using sensors.
 
This project demonstrates embedded systems, sensor integration, and automated waste management, which are important concepts in AIoT and smart city solution


----------PROJECT OVERVIEW 👁️----------

Waste segregation is an important step in improving recycling efficiency. Manual segregation is slow and inefficient.
This system automates the process by:
    1 - Detecting waste using sensors
    2 - Rotating the bin to the correct section
    3 - pening the lid automatically
    4 - Monitoring environmental conditions
The project is designed using Arduino and multiple sensors, making it suitable for prototype smart waste management systems.


----------FEATURES 🌟----------

  ▶ Automatic waste detection
  ▶ Stepper motor based bin rotation
  ▶ Servo motor controlled lid
  ▶ Metal detection using proximity sensor
  ▶ Object detection using IR sensor
  ▶ Environmental monitoring using DHT22 sensor
  ▶ Modular design for future AI integration
  ▶ Easy to expand with IoT dashboards


  ----------HARDWARE COMPONENTS 🖱️----------

  Component                           |           Quantity
--------------------------------------|-------------------------------
Arduino UNO	                          |           1
Stepper Motor                         |           1
A4988 Stepper Motor Driver            |           1
Servo Motor                           |           1
IR Sensor                             |           1
Metal Proximity Sensor                |           1
Raindrop Sensor                       |           1
DHT22 Temperature & Humidity Sensor   |           1
Limit Switch                          |           1
Power Supply                          |           1
Jumper Wires                          |           As Required
Waste Bin Prototype Structure         |           1


 ----------SYSTEM ARCHITECTURE 📐----------

 Waste Detection
     ▶
Sensors Trigger Controller
(Dry / Metal / Wet)
     ▶
Arduino Processes Input
     ▶
Stepper Motor Rotates Bin
(A4988 Driver)
     ▶
Servo Motor Opens Lid
     ▶
Waste Drops into Correct Compartment


----------WORKING PRINCIPLE ⚙️----------

   ▶ The IR sensor detects when waste is placed near the input area(Dry waste).
   ▶ The metal proximity sensor checks if the waste is metallic.
   ▶ The raindrop sensor checks if the waste is wet.
   ▶ The Arduino processes sensor data to determine the category.
   ▶ The stepper motor rotates the bin to the correct compartment.
   ▶ The servo motor opens the lid to allow the waste to drop.
   ▶ The system then returns to its original position for the next input.


----------Pin Configuration (Example) 🖇️----------

  Component                           |           Arduino Pin
--------------------------------------|-------------------------------
A4988 STEP	                          |           D6
A4988 DIR                             |           D7
A4988 ENABLE                          |           D8
IR Sensor                             |           D2
Raindrop sensor                       |           A0
Servo Motor                           |           D9
Metal Sensor                          |           D3
DHT22 / DHT11                         |           D4
Limit Switch                          |           D5

For POWER SUPPLY 🪫: VCC(Arduino, Driver) - 12v, VCC(sensors, Driver) - 5V (From Arduino), GND common. 


----------SIMULATION 💻----------

The project can be tested using Wokwi simulator for:
    ⇨ Stepper motor testing
    ⇨ Sensor interaction
    ⇨ Logic validation


----------APPLICATIONS 🧾----------

  1) Smart Cities
  2) Automated Recycling Systems
  3) Industrial Waste Segregation
  4) Smart Dustbins
  5) Environmental Monitoring Systems


----------FUTURE IMPROVEMENTS 📈----------

   ⋙ Add AI-based waste classification using camera
   ⋙ Integrate IoT dashboard for monitoring
   ⋙ Use machine learning for waste recognition
   ⋙ Cloud data logging
   ⋙ Mobile app control


----------LEARNING OUTCOMES 📤----------

This project demonstrates practical experience in:

   ⇒ Embedded Systems Programming
   ⇒ Sensor Interfacing
   ⇒ Stepper Motor Control
   ⇒ Servo Motor Control
   ⇒ Automation Systems
   ⇒ Smart Waste Management Concepts


--------------------------------------------------------------------------------------------------------------------------------------
AUTHOR : 
V Harsha Teja
Electronics & Communication Engineering
Interested in AIoT, IIoT, and Embedded Systems

GitHub: https://github.com/Harsha-0605

License:
This project is open-source and available under the MIT License.
