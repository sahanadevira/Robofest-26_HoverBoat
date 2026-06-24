# Bluetooth Controlled Hover Boat using Arduino UNO
A simple Bluetooth-controlled hover boat project built using an Arduino UNO and motor driver. The boat receives commands from a Bluetooth-enabled smartphone and performs forward, backward, left, right, and stop movements.
# Features
Wireless Bluetooth control
Forward movement
Backward movement
Left turn
Right turn
Stop function
Simple Arduino implementation
Beginner-friendly project
# Hardware Requirements
Arduino UNO
Bluetooth Module (HC-05 / HC-06)
Motor Driver Module (L298N or similar)
DC Motors
Hover Boat Chassis
Battery Pack
Connecting Wires
Smartphone with Bluetooth Controller App
# Pin Connections
Arduino UNO
Motor Driver
D2
IN1
D3
IN2
D4
IN3
D5
IN4
Bluetooth Module
Bluetooth Module
Arduino UNO
TX
RX
RX
TX
VCC
5V
GND
GND
Note: For reliable communication, SoftwareSerial can also be used instead of the hardware serial pins.
# Bluetooth Commands
Command
Action
F
Move Forward
B
Move Backward
L
Turn Left
R
Turn Right
Any Other Character
Stop
# Working Principle
The smartphone sends a command through Bluetooth.
The HC-05/HC-06 module receives the command.
Arduino reads the incoming character through serial communication.
Based on the received command:
F → Forward
B → Backward
L → Left
R → Right
The Arduino controls the motor driver pins accordingly.
Motors rotate in the required direction, moving the hover boat.
