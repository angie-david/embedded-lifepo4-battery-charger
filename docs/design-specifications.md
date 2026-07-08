# Design Specifications

## System Overview

This document defines the engineering specifications and design constraints for the embedded LiFePO₄ battery charging controller.

---

## Preliminary Specifications

| Parameter | Value |
|-----------|-------|
| Battery Chemistry | LiFePO₄ |
| Output Voltage | 14.6 V |
| Converter Topology | Synchronous Buck |
| Controller | STM32 |
| Charging Algorithm | CC-CV |
| Switching Frequency | 100 kHz |
| Operating Mode | CCM |

---

## Design Variables

The following parameters will be determined through MATLAB design-space optimization.

| Parameter | Range |
|-----------|-------|
| Input Voltage | 18–60 V |
| Output Power | TBD |
| Charge Current | TBD |
| Inductor Ripple | TBD |
| Output Voltage Ripple | TBD |

---

## Design Objective

Determine the converter operating point and component values that maximize efficiency while satisfying the required charging specifications.
