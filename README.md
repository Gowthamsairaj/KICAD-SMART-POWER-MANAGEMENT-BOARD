View this project on [CADLAB.io](https://cadlab.io/project/29900). 

# Smart Power Management Board  
Buck Converter + LDO Regulation + Input Protection

## 📌 Project Overview
This project is a compact and efficient power supply system designed to convert a higher DC input voltage into stable 5V and 3.3V outputs suitable for microcontrollers, sensors, and embedded platforms.

The board demonstrates practical power tree design, regulator selection, protection techniques, and PCB layout practices used in real products.

---

## 🎯 Features
- Wide DC input range (e.g., 12V–24V)
- Buck conversion to 5V
- Linear regulation to 3.3V
- Reverse polarity and surge protection
- Output filtering capacitors
- Test points for debugging
- Screw terminal I/O connectors
- Designed for manufacturability

---

## 🧠 System Architecture
DC Input → Protection → Buck (5V) → LDO (3.3V) → Load


---

## 🔧 Main Components
- LM2596 – Step-down buck regulator
- AMS1117-3.3 – Linear regulator
- Schottky diode – reverse protection
- TVS diode – surge suppression
- Inductor & capacitors – filtering
- Potentiometer – output adjust (if used)

---

## ⚡ Output Rails
| Rail | Purpose |
|------|--------|
| 5V   | Motors, relays, logic supply |
| 3.3V | MCU, sensors, communication modules |

---

## 🛡 Protection Implemented
- Input reverse polarity protection
- Over-voltage transient suppression
- Fuse / polyfuse ready design
- Bulk and decoupling capacitors

---

## 📐 PCB Design Highlights
- Separate power and signal routing
- Short high-current paths
- Proper grounding strategy
- Wide traces for power lines
- Industry standard footprints

---

## 🧪 Ideal Applications
- Embedded development boards
- IoT prototypes
- Industrial control units
- Robotics
- Automation projects

---

## 🚀 What This Project Demonstrates
- Understanding of DC-DC conversion
- Power integrity basics
- Thermal & current considerations
- Schematic to PCB workflow
- ERC / DRC clean design

---

## 🧰 Tools Used
- KiCad (Schematic & PCB)
- GitHub for version control

---

## 👤 Author
[Your Name]

Electronics & Communication Engineering  
Interested in Embedded Systems & Hardware Design

---

## 📜 License
Open-source for learning and educational use.
