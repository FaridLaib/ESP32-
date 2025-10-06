# ESP32-S2 compatible with ESP32-S3 or any other model including Arduino Micro or Pro
This project turns an ESP32-S2 into a USB HID gamepad that can receive commands over Serial (UART or USB Serial) to simulate button presses on a connected device — such as a PC, console adapter, or input relay (e.g., XIM Matrix).


🧩 Features

Emulates a USB HID gamepad using the USBHIDGamepad library
Supports up to 20 buttons
Listens to commands from the Serial interface
Executes press and release actions with 500 ms intervals
Includes an auto-wake sequence that presses the X button (Button 3) on startup


⚙️ Hardware Requirements

ESP32-S2 board with native USB support 
Micro-USB cable
Host device that accepts HID gamepad input (e.g., PC, console adapter, XIM Matrix, Cronus Zen)
