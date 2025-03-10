# PFC_IT_NE_effect

## Overview
**PFC_IT_effect** is a computational neuroscience project investigating the influence of **intratelencephalic (IT) neurons** in the **prefrontal cortex (PFC)** on network dynamics and information processing. The project explores how IT neurons modulate coscillatory behavior in both control and pathological conditions (e.g., Parkinson’s disease).

## Research Objectives
- Analyze the role of IT neurons in the PFC.
- Investigate their influence on **oscillatory dynamics, and network states**.
- Compare computational model results with experimental data.
- Examine the effects of NE on IT activity.
- **Tune IT model parameters to match the FI curve** for experimental data in:
  - **Baseline (no NE applied)**
  - **NE applied condition**

## Methodology
This project employs:
- **Computational models using neuron and NetPyNE** for single cell and network simulations.
- **F-I curve tuning** to calibrate IT neuron responses to experimental data.
- **LFP and spike data analysis** to measure power spectral density, modulation index.
- **Comparison of control and Parkinsonian conditions** to understand how IT neurons contribute to disease-related network changes.

## Requirements
To run the simulations and analyses, you need:
- Python 3.8+
- [NetPyNE](https://www.netpyne.org/)
- NumPy, SciPy, Matplotlib, and Pandas
- Additional libraries for signal processing:
  ```sh
  pip install numpy scipy matplotlib pandas netpyne neo elephant


