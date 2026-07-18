# ECG Signal Acquisition Front-End

## Overview

This project implements a simulated ECG (Electrocardiogram) signal acquisition system using LTspice. The design demonstrates how weak biopotential signals can be amplified, filtered, and conditioned before being interfaced with an Analog-to-Digital Converter (ADC).

The project focuses on analog front-end design principles commonly used in biomedical instrumentation and embedded sensing applications.

---

## Features

- Instrumentation amplifier for differential ECG signal amplification
- High-gain analog signal conditioning
- Active low-pass filtering
- AC coupling for baseline drift removal
- Designed for ADC-compatible output
- LTspice simulation

---

## Software Used

- LTspice XVII

---

## Circuit Blocks

ECG Signal Source
↓
Instrumentation Amplifier
↓
Differential Gain Stage
↓
AC Coupling Network
↓
Active Low-Pass Filter
↓
Conditioned ECG Output

---

## Components Used

- UniversalOpAmp2
- Precision resistors
- Capacitors
- DC power supplies
- Simulated ECG waveform (PWL)

---

## Simulations Performed

- Transient Analysis
- Signal Amplification Verification
- ECG Waveform Observation
- Filter Response Validation

---

## Learning Outcomes

- Instrumentation amplifier design
- Differential signal amplification
- Active filter design
- Biomedical signal conditioning
- Analog circuit simulation

---

## Future Improvements

- Add 50 Hz notch filter for power-line interference rejection
- Replace UniversalOpAmp with a real instrumentation amplifier (INA333 / INA128)
- Interface with STM32 ADC
- Add right-leg drive circuit
- Fabricate and test physical PCB


---

## Author

Vatsalsinh Bhati

B.Tech Electrical Engineering

Nirma University
