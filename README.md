# Embedded LiFePO₄ Battery Charging Controller

## Overview

This project focuses on the design and implementation of an embedded LiFePO₄ battery charging controller using an STM32 microcontroller and a synchronous buck converter. The charger implements a Constant Current / Constant Voltage (CC-CV) charging algorithm and is being developed through analytical modeling, simulation, PCB design, and embedded firmware implementation.

---

# Design Specifications

| Parameter | Specification |
|-----------|---------------|
| Battery Chemistry | LiFePO₄ |
| Battery Charge Voltage | 14.6 V |
| Converter Topology | Synchronous Buck |
| Controller | STM32 |
| Charging Algorithm | CC-CV |
| Switching Frequency | 100 kHz |
| Input Voltage | Design Variable (18–60 V) |
| Operating Mode | CCM |

---

# Design Methodology

1. Design specification selection
2. MATLAB design-space optimization
3. Component selection
4. LTspice verification
5. PCB design
6. STM32 firmware implementation
7. Hardware validation

---

# Current Results

| Category | Result |
|----------|--------|
| Topology | Synchronous Buck Converter |
| Controller | STM32 |
| Switching Frequency | 100 kHz |
| Battery Voltage | 14.6 V |
| Operating Mode | CCM |
| Input Voltage | Under optimization (18–60 V) |
| MATLAB Design Space Sweep | In Progress |
| Component Selection | In Progress |

---

# Repository Structure

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

# Software

- MATLAB
- LTspice
- STM32CubeIDE
