# Temperature-Sensor-with-ATmega32

This project implements a **temperature sensor** using the **ATmega32** microcontroller. The system continuously measures the temperature, and if the temperature exceeds a predefined threshold, it activates a fan and displays a warning on the **LCD**.

## Features
- Real-time temperature measurement using a temperature sensor (e.g., LM35)
- Fan activation when the temperature exceeds the threshold
- Warning message displayed on **LCD 16x2** when temperature is high
- Simple and effective temperature monitoring system

## Setup and Installation
1. **Hardware Setup**:
   - **ATmega32** microcontroller
   - **LM35** temperature sensor (or any suitable analog sensor)
   - **LCD 16x2** for displaying temperature and warnings
   - **Fan** connected via a transistor or relay for activation
2. **Flashing the Code**:
   - Open the code in **Atmel Studio** or **AVR-GCC** and upload it to the microcontroller.
3. **Usage**:
   - The system continuously reads the temperature.
   - If the temperature exceeds the threshold, the fan turns on, and a warning message appears on the LCD.

## Contributing
If you'd like to contribute, feel free to fork the project and submit your changes.
