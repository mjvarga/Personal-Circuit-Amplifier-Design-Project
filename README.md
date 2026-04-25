# Personal-Circuit-Amplifier-Design-Project
Private Repository Disclaimer: If you have access to this repository please keep in mind that this work is only for my personal and archival/backup purposes only. Not for distribution or academic misconduct. Please adhere to POLICY 60, created by Toronto Metropolitan University to avoid academic misconduct.

# Multi-Stage MOSFET Voltage Amplifier Design

<img width="1405" height="772" alt="image" src="https://github.com/user-attachments/assets/43957368-b394-4cdd-a5be-de53e03615f7" />
<img width="1384" height="507" alt="image" src="https://github.com/user-attachments/assets/4cf89c25-0870-4a00-a759-41b0b5ffb801" />

## Overview

This project presents the design, theoretical analysis, and simulation of a four-stage MOSFET voltage amplifier developed for ELE404 – Electronic Circuits I at Toronto Metropolitan University.

The amplifier was designed to satisfy strict performance specifications including:

* Open-loop gain ≥ 60 dB
* Bandwidth ≥ 500 kHz
* Input resistance ≥ 100 kΩ
* Output swing ≥ 1.5 Vpp
* Power consumption ≤ 1 mW
* Gain reduction with load ≤ 10%

The final design successfully exceeded all required specifications using a multi-stage architecture consisting of:

* Stage 1: NMOS Common-Source Amplifier
* Stage 2: NMOS Common-Source Amplifier
* Stage 3: PMOS Common-Source Amplifier
* Stage 4: NMOS Source Follower (Buffer Stage)

---

## Final Performance Results

| Parameter         | Simulated Value |     Requirement |
| ----------------- | --------------: | --------------: |
| Open-loop Gain    |        64.62 dB |         ≥ 60 dB |
| Gain with Load    |        61.40 dB | ≤ 10% reduction |
| Gain Reduction    |           4.98% |           ≤ 10% |
| Output Swing      |        1.66 Vpp |       ≥ 1.5 Vpp |
| Power Consumption |         0.96 mW |          ≤ 1 mW |
| Bandwidth         |      ~11–12 MHz |       ≥ 500 kHz |
| Input Resistance  |          405 kΩ |        ≥ 100 kΩ |

---

## Design Highlights

### Stage 1 & 2 – NMOS Common-Source Amplifiers

These stages provide the initial voltage amplification with moderate gain and stable biasing.

### Stage 3 – PMOS Common-Source Amplifier

Used to increase gain further and improve output voltage swing.

### Stage 4 – NMOS Source Follower

Acts as a buffer stage to reduce gain degradation when connected to the load resistance.

---

## Simulation Tools

* KiCad SPICE Simulation
* Manual Small-Signal Analysis
* MOSFET Biasing Calculations

---

## Circuit Schematic

(Add your Figure 1 screenshot here)

---

## Frequency Response

(Add your Figure 2 screenshot here)

---

## AC Waveform Analysis

(Add your Figure 3 screenshot here)

---

## Key Learning Outcomes

* Multi-stage amplifier design
* MOSFET biasing and sizing
* Small-signal gain analysis
* Frequency response optimization
* Output buffering techniques
* Practical simulation verification

---

## Project Report

Full technical report available in this repository:

`ELE404_Final_Project_Report.pdf`

---

## Author

Michael Varga

Electrical Engineering
Toronto Metropolitan University

---

## License

This project is for academic and educational purposes.
