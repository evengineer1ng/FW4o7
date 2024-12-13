# DIY Sim Racing Steering Wheel Project

This project is a custom-built DIY sim racing steering wheel designed to be a robust competitive wheel in sim racing games used with a 3rd party wheelbase and pedals, or without them. When you switch to gyroscope mode you can turn the car in thin air with no wheelbase or pedals, kind of like the Mario Kart Wiimote, but unlike the Wiimote, there is no sensor on the other side of the room. Everything needed to make this an effective sim racing wheel is housed within the wheel. Also, there is an optional third mode for RC car control. 


🛠️ Required Hardware

•	Programmable LED light strip: i.e. NeoPixels
 
•	3.5 inch TFT display: i.e. Nextion Discovery 3.5"
•	Magnetic Hall Sensors: SS49E hall sensors
•	Joysticks: PS5 joysticks

•	IMU Module: MPU6050 gyroscope module

•	Power Supply: Phone power bank that is under 9.5 cm tall and under 8.5 cm wide. The port for charging the power bank should be in the middle of the power bank.

•	ESP32 BT + WiFi Microcontroller and a Teensy 4.0 Microcontroller

• 4x NO microswitches with an arm lever 

• 12x SPST pushbutton switches

• DRV 8833 for driving motors

• Xbox 360 controller rumblers

• Phone vibration motors

• 12mmx5mm Magnets

• 3D printed parts

• 3rd party Metal Quick Release for your wheelbase (if you're using one): I use a Kyostar QR for my Moza R9

• Jumper wires + soldering

• 2x USB-C breaker board. One for data (connecting to PC by USB), another for power (connecting by USB to power bank, then using board's pins to power higher end peripherals like the motors and lights)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This project uses a custom python script/application for processing game data and delivering it to the wheel’s display and lights, as well as the motors. 

📡 Connectivity
	•	Will be able to connect to PC by Bluetooth, WiFi or USB

This is a work in progress. Most of the project is done but there is still some progress to be made before showing this around. Will continue to update here. 
