# Superheterodyne Receiver Design Project

This repository contains the analysis and design documentation for a **superheterodyne RF receiver** operating in the 3.4 – 3.6 GHz frequency range. The project includes component selection, frequency planning, and block diagram representations for both the receiver and its frequency synthesizer.

## 📡 Project Objective

The goal of this project is the design and evaluation of a superheterodyne receiver. The process includes:

- Selection of RF components using the [everythingRF](https://www.everythingrf.com/) platform
- Analysis of component specifications and performance limits
- Frequency planning for 10 distinct central frequencies within the band
- Design of a frequency synthesizer to drive the mixing stage
- Block diagram representations for both the receiver and synthesizer

## 🔍 System Overview

- **Operating Band:** 3.4 – 3.6 GHz  
- **Bandwidth per Channel:** 20 MHz  
- **Number of Channels:** 10 central frequencies  
- **Intermediate Frequency (IF):** [To be specified in the report]  
- **Synthesizer Output Frequencies:** 2654 + 20 * *i* MHz for *i* = 1 to 10

The synthesizer is designed to provide local oscillator (LO) signals to downconvert the input RF signal to the intermediate frequency.
## 🛠️ Tools & Resources

- [everythingRF](https://www.everythingrf.com/) for component selection
- Block diagram tools (e.g., draw.io, MATLAB, Visio)
- MATLAB or Python for signal analysis (if applicable)

## 📊 Deliverables

- Receiver block diagram  
- Frequency synthesizer block diagram  
- Frequency mapping table for all signal stages  
- Component analysis and justifications  
- Full technical report (PDF)

