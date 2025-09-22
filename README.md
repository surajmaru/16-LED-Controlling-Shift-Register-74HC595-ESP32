16-LED Controlling with Shift Register (74HC595 + ESP32)

This project demonstrates how to control 16 LEDs using an ESP32 and two cascaded 74HC595 shift registers. By using shift registers, you can expand the number of output pins while only using a few GPIO pins from the ESP32.

✨ Features

Control up to 16 LEDs with just 3 pins of ESP32

Demonstrates cascading 74HC595 shift registers

Simple wiring diagram for beginners

Example Arduino code included (works with ESP32)

Easy to expand for more LEDs or outputs

🛠️ Components Required

ESP32 development board

2 × 74HC595 shift registers

16 × LEDs

16 × Resistors (220Ω recommended)

Breadboard + jumper wires

USB cable for programming ESP32

🔌 Wiring (Basic)

Connect the data, latch, and clock pins of ESP32 to the first 74HC595

Cascade the second 74HC595 to the first (Q7’ to DS)

Connect LEDs with current-limiting resistors to the output pins (Q0–Q7 of each chip)

Common ground between ESP32 and the circuit

📂 Code

Example code is provided in this repository. It shifts out bits to the registers to control the LEDs in patterns (like blinking, chasing, etc.).

▶️ Usage

Upload the provided code to your ESP32

Open Serial Monitor (optional) to see debug messages

Observe LEDs turning ON/OFF in sequence and patterns

video link:- https://youtu.be/Mnlt46S9PX0?si=Jtnvl4u-IxroH4Ns
