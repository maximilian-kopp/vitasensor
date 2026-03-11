# VitaSensor System Architecture

## Overview

VitaSensor integrates three core subsystems into a compact wearable form factor:

### 1. Optical Sensing Module
- Flexible GeSe-based nanomaterial photodetector array
- Exploits in-plane anisotropy of 2D GeSe for polarizer-free chiroptical detection
- Broadband optical response optimized for glucose absorption signatures

### 2. Signal Processing & ML Calibration
- Real-time signal acquisition from photodetector array
- Machine learning calibration pipeline (R² = 0.94, MAE ≈ 8.6 mg/dL)
- Adaptive noise filtering for motion artifact rejection

### 3. Hardware & Embedded Systems
- Custom PCB with low-power microcontroller
- Bluetooth Low Energy (BLE) data transmission
- Flexible substrate for comfortable skin contact

## Data Flow

```
Skin → GeSe Photodetector → Analog Frontend → ADC → MCU → ML Model → Glucose Reading → BLE → Mobile App
```

## Fabrication

- Nanomaterial synthesis and deposition
- Flexible substrate lamination
- Inkjet printing for scalable manufacturing pathway
