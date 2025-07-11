# DIY Lab Bench Power Supply

## Project Overview

Design and build an adjustable lab power supply that offers:

- Constant Voltage (CV) regulation  
- Constant Current (CC) limiting  
- User interface via potentiometer, digital display, or optional microcontroller (e.g., PIC or AVR)

---

## 1. Design Goals and Specifications

Define your power supply’s operating range and core specs:

- Output range (e.g., 0–30 V, 0–3 A)
- Voltage and current regulation accuracy
- Smooth and safe transition from CV to CC mode

---

## 2. Topology Exploration

Start with a basic linear power supply design:

- Use a linear regulator like LM317 with a pass transistor for increased current capability
- Consider alternatives like the LT3080 for low-dropout and modular design options

---

## 3. Control Strategy

Determine how the user will interact with the supply:

- Analog control using potentiometers (simple and effective)
- Optional digital control using a microcontroller for push-button input and digital display

---

## 4. Circuit Design

Core components include:

- A precision voltage reference and error amplifier for voltage regulation
- A sense resistor and comparator or op-amp circuit for current limiting
- Automatic mode switching between CV and CC based on output load

---

## 5. Prototype and Testing

- Build a prototype on breadboard or perfboard
- Measure voltage and current under various loads
- Test the stability and response of both CV and CC modes

---

## 6. Component Optimization

- Select and test appropriate pass transistors and heatsinking
- Improve transient response and reduce output noise
- Add features such as reverse polarity protection and thermal shutdown

---

## 7. Optional Enhancements

- Digital display for voltage and current readout
- Microcontroller integration for presets and menus
- Over-temperature protection, soft-start, or relay-based switching

---

## Deliverables

- Complete schematic and PCB layout files (KiCad, Altium, or similar)
- Bill of Materials (BOM) with part numbers and suppliers
- Testing documentation with oscilloscope screenshots and load tests
- Firmware (if microcontroller is used)
- Final documentation including block diagram, design explanation, and user guide

---

## Learning Outcomes

- Understanding of analog feedback control in power supplies
- Hands-on skills in building and testing CV/CC regulators
- Knowledge of thermal design, PCB layout, and power device handling
- Optionally, experience integrating analog and digital control systems
