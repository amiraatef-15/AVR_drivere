# AVR_driveres


A structured and modular collection of drivers for AVR Microcontrollers, specifically designed for the ATmega32.

📌 Overview

This repository includes low-level drivers written in C, built with a layered architecture (MCAL & HAL) to allow easy portability, readability, and reuse in embedded projects.

📁 Driver List

✅ MCAL Layer
- DIO (Digital Input/Output)
- ADC (Analog-to-Digital Converter)
- TIMER (Timer0, Timer1, Timer2)
- USART (Serial Communication)
- SPI
- I2C
- External Interrupts
- EEPROM

✅ HAL Layer
- LCD
- Keypad
- DC Motor
- Servo Motor
- Buzzer
- LED
- Temperature Sensor (LM35)
  

⚙️ Microcontroller Used
- ATmega32

💡 Features
- Clean code structure
- Layered abstraction (MCAL → HAL)
- Reusable modules
- Well-documented driver interfaces

🛠️ Tools
- AVR-GCC
- Eclips
- Proteus (for simulation)
- AVR Dude / USBasp (for programming)

📬 note:
there is a test and simple project for all drivers in main file
