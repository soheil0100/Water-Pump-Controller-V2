# Water Pump Controller System V2

An automatic water pump control system developed using Arduino for intelligent water level management.
 
This system monitors water level conditions and controls the pump automatically to prevent overflow or dry running.

---

## Overview

The Water Pump Controller is designed to automate water tank management.

The system:

- Detects water level using sensors
- Automatically turns pump ON when water is low
- Turns pump OFF when tank is full
- Prevents dry-run operation

Suitable for:

- Residential water tanks
- Agricultural irrigation systems
- Small industrial applications

---

## Features

- Automatic pump control
- Water level detection
- Overflow protection
- Dry-run prevention
- Relay-based motor control
- Proteus simulation included
- HEX file available

---

## Hardware Components

- Arduino Uno
- Water Level Sensors
- Relay Module
- Water Pump
- Power Supply

---

## Software

- Arduino IDE (.ino source included)
- Proteus simulation project
- Compiled HEX file

---

## Project Structure

```
Water-Pump-Controller/
/
/// firmware/
/ /// water_pump_controller.ino
/
/// simulation/
/ /// proteus-project.pdsprj
/
/// images/
    /// simulation.png
```

---

## Working Principle

1. Water level sensors monitor tank condition.
2. When level drops below minimum threshold:
   - Pump is activated.
3. When tank reaches maximum level:
   - Pump is deactivated.
4. System continuously monitors sensor state.

---

## Future Improvements

- LCD display for level indication
- GSM notification system
- IoT monitoring via WiFi
- PCB board design
- Overcurrent protection circuit

---

## License

This project is licensed under the MIT License.

---

## 👥 Authors

Developed collaboratively by:

- Soheil Ahmadi
- Omid Menbari
  
Open-source embedded control project.
