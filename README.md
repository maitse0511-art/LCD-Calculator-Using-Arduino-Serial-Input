# LCD-Calculator-Using-Arduino-Serial-Input
An Arduino-based calculator system that accepts numeric inputs and arithmetic operators via the Serial Monitor and displays results on a 16×4 LCD.


LCD Calculator Using Arduino & Serial Input:
An Arduino-based calculator system that accepts numeric inputs and arithmetic operators via the Serial Monitor and displays results on a 16×4 LCD. The project demonstrates serial communication, LCD interfacing, and control logic in embedded systems.

Features
Serial-based numeric input (Value A & Value B)
Operator selection: +, -, *, /
Real-time result display on LCD
Simple human–machine interface
Modular and readable embedded C/C++ code

Technical Overview:
The system uses the Arduino’s UART interface to receive user input via the Serial Monitor. Integer values are parsed using Serial.parseInt(), while arithmetic operators are handled using string comparison logic.
A 16×4 LCD is driven in parallel mode using the LiquidCrystal library, enabling real-time display of prompts and calculation results.

Hardware Used:
Arduino Uno
16×4 LCD (parallel interface)
USB serial connection
Jumper wires

Skills Demonstrated:
Embedded C/C++ (Arduino)
Serial communication (UART)
LCD interfacing
Control flow & input validation
Debugging and system testing

Future Improvements:
Non-blocking serial input using millis()
Keypad-based input (standalone calculator)
Division-by-zero protection
Floating-point calculations
Improved UI formatting

