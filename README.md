# Biomedical Capnography Monitor

A non-invasive clinical diagnostic prototype designed to monitor exhaled CO2 concentration and breathing waveform in real-time.

## Hardware & Components
- Microcontroller: Arduino Mega 2560
- Display: 3.5-inch TFT Display
- Sensor: Calibrated NDIR CO2 Sensor and Heart rate sensor
- Power: 5V DC regulated power supply

## Tech Stack & Communication
- **Firmware:** Embedded C 
- **Protocol:** UART Serial Communication for calibrated sensor data
- **Graphics:** Adafruit GFX / MCUFRIEND_kbv display driver libraries

## Key Features
- Continuous real-time plotting of capnogram waveform on the 3.5" TFT.
- Accurate End-Tidal CO2 (EtCO2) and respiratory rate estimation.
- Visual limit alerts for abnormal CO2 levels.
