# embedded-lifepo4-battery-charger
Embedded STM32-based CC-CV LiFePO4 battery charger using a synchronous buck converter with MATLAB optimization, LTspice simulation, and custom PCB design.
# Embedded LiFePO4 Battery Charger

## Overview

This project investigates the design and implementation of an embedded LiFePO4 battery charging controller using an STM32 microcontroller and a synchronous buck converter. The objective is to develop a custom constant-current/constant-voltage (CC-CV) charging system while gaining practical experience in power electronics, embedded systems, and PCB design.

The project is being developed as part of undergraduate research at UC San Diego.

---

## Objectives

- Design a synchronous buck converter for LiFePO4 battery charging
- Implement a digital CC-CV charging algorithm on an STM32 microcontroller
- Optimize converter specifications using MATLAB parameter sweeps
- Verify converter operation using LTspice simulations
- Design and fabricate a custom PCB
- Validate charging performance through hardware testing

---

## Current Progress

✔ Studied LiFePO4 CC-CV charging methodology

✔ Analyzed the LT3741 battery charger architecture

✔ Defined preliminary system architecture

✔ Selected STM32 as the embedded controller

✔ Selected synchronous buck converter topology

✔ Established initial design specifications

- Input voltage: 18–60 V (design space)
- Output voltage: 14.6 V
- Switching frequency: 100 kHz
- Operation mode: CCM

🚧 Current Work

- MATLAB design-space optimization
- Converter component calculations
- Inductor and capacitor selection

---

## Planned Workflow

```
Design Specifications
        │
        ▼
MATLAB Design Space Sweep
        │
        ▼
Component Selection
        │
        ▼
LTspice Verification
        │
        ▼
PCB Design
        │
        ▼
STM32 Firmware
        │
        ▼
Hardware Validation
```

---

## Repository Structure

```
docs/
matlab/
ltspice/
firmware/
pcb/
datasheets/
images/
```

---

## Software

- MATLAB
- LTspice
- STM32CubeIDE
- Git & GitHub

---

## Project Status

🟢 Active Development (Summer 2026)
