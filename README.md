A Bluetooth Controlled Car is an IoT/embedded systems project where a small robotic vehicle is controlled wirelessly using a smartphone or any Bluetooth-enabled device. It is commonly built using an Arduino Uno, a Bluetooth module like HC-05 Bluetooth Module, and a motor driver such as L298N Motor Driver.

🔧 Working Principle

The system receives commands from a mobile app via Bluetooth. These commands are sent to the Arduino, which processes the input and controls the motors accordingly through the L298N driver. The driver then regulates the direction and speed of the DC motors, allowing the car to move forward, backward, left, right, or stop.

📱 Control Method

Controlled using Android Bluetooth apps like “Bluetooth RC Controller”
Commands are sent as characters (e.g., F = forward, B = backward, L = left, R = right, S = stop)

⚙️ Main Components

Arduino Uno (controller)
HC-05 Bluetooth module (wireless communication)
L298N motor driver (motor control)
DC motors + chassis (movement system)
Battery supply (power source)

🚗 Features

Wireless control via smartphone
Real-time movement response
Easy to build and modify
Useful for learning embedded systems and robotics basics

🎯 Applications

Robotics learning projects
IoT demonstrations
Academic mini-projects
Prototype for automation systems
