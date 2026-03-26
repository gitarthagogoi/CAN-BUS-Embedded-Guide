# CAN-BUS-Embedded-Guide
A practical guide to implementing and debugging Controller Area Network communication using STM32 and ESP32, covering bit timing, error handling, and real-world troubleshooting.

A practical, experience-driven guide to understanding and debugging CAN (Controller Area Network) communication in embedded systems.
![CAN Bus Diagram](diagrams/can-setup.png)

---

## Overview

This repository focuses on building a strong foundation in CAN communication, with emphasis on **real-world debugging and understanding** rather than just implementation.
It is based on hands-on experience working with CAN across STM32 and ESP32 platforms.

---

## What This Repository Covers (So Far)

Currently, the repository includes:

### CAN Basics
- What CAN is and how it works  
- Frame structure and arbitration  
- Standard vs extended IDs  
- Communication model  

👉 `docs/CAN_Basics.md`

---

### Bit Timing
- Time quanta and bit segmentation  
- Baud rate calculation  
- Importance of timing alignment  
- Why small mismatches break communication  

👉 `docs/Bit-Timing.md`

---

### Common Errors & Debugging

#### Physical Layer Debugging
- CAN_H / CAN_L wiring issues  
- Termination resistor importance  
- Slope control (Rs pin)  
- Grounding and power issues  

#### Software Configuration Issues
- Bit timing mismatch  
- Filter misconfiguration  
- Mode selection (normal vs loopback)  
- Interrupt and initialization issues  

#### Advanced Debugging
- No ACK conditions  
- Error counter analysis (TEC/REC)  
- Intermittent communication issues  
- Cross-platform timing mismatch  

👉 `troubleshooting/Common_Errors.md`

---

## Goal of This Repository

The goal is to help developers:
> Move from “CAN is not working” → “I understand exactly why it is not working”

---

## Work in Progress (Upcoming Additions)
This repository will be expanded with:
- STM32 CAN implementation examples  
- ESP32 (TWAI) implementation examples  
- Cross-platform comparison (STM32 vs ESP32)  
- Step-by-step debugging flow  
- Logic Analyzer signal analysis 

---

## Important Note
- This is a clean, independent learning resource  
- No proprietary or company-specific code is included  
- All content is simplified for clarity and practical understanding  

---

## 🤝 Contributions & Feedback

If you have faced interesting CAN issues or have suggestions, feel free to open an issue or contribute.

---

## ⭐ Support

If you find this useful, consider giving it a star ⭐
