# ESP32-PortaPack-Mesh-Network-Project

ESP32-PortaPack Mesh Network Project

Overview
This project aims to create a mesh network using ESP32 devices that communicate via the ESP-NOW protocol, all controlled by a PortaPack running custom firmware. The PortaPack will serve as the user interface, allowing the user to send commands to a master ESP32, which will then coordinate tasks among the slave ESP32 nodes.

Features
Mesh Network Communication: Utilize ESP-NOW for efficient, low-latency communication between nodes.

PortaPack Control Interface: Send commands from the PortaPack to the master ESP32 using the GPIO pins.

Distributed Wi-Fi Scanning: Coordinate multiple nodes to perform synchronized Wi-Fi scans.

Real-Time Signal Mapping: Visualize node locations and signal strengths on a map interface.

Customizable Commands: Implement features like deauthentication, channel hopping, and more.

Getting Started
Set Up the ESP32 Environment: Use the Arduino IDE initially for simplicity. Install the ESP32 board package and set up the necessary libraries.

Build the Master Firmware: Create firmware for the master ESP32 that can receive and interpret commands from the PortaPack.

Develop the Slave Firmware: Program the slave ESP32s to respond to the master’s commands and perform the desired tasks.

Create the PortaPack App: Develop a custom app for the PortaPack that can send predefined commands to the master ESP32 via the GPIO pins.

Test and Iterate: Test the communication between the PortaPack and the master ESP32, and then test the mesh network functionality. Make adjustments as needed.

License
This project is licensed under the MIT License.
