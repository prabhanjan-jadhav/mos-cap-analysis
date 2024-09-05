# C-V Characteristics of MOS Capacitor

This repository contains the simulation and analysis of the C-V characteristics of a MOS capacitor using Scaps software. The project was part of **EE313: Microelectronics Laboratory** course.

## Table of Contents

- [Overview](#overview)
- [Experiments](#experiments)
- [Results](#results)
- [Comparison](#comparison)
- [Analysis](#analysis)

## Overview

This project focuses on analyzing the capacitance-voltage (C-V) characteristics of a Metal-Oxide-Semiconductor (MOS) capacitor. The study includes simulating the C-V characteristics under various conditions, such as varying gate voltage, gate metal work function, substrate doping density, and oxide thickness.

## Experiments

### 1. Basic C-V Plot
- **Objective:** Simulate a MOS capacitor with varying gate voltage from -2V to 2V.
- **Parameters:** Use parameters from the given figure.
- **Output:** Obtain the C-V plot and extract values of Cox, VTH, VFB, and Qox.

### 2. Variation of VTH with Gate Metal Work Function
- **Objective:** Analyze the effect of different gate metal work functions on threshold voltage (VTH).
- **Parameters:** Use 4 different metals for the gate.
- **Output:** Plot VTH vs. Gate Metal Work Function.

### 3. C-V Characteristics with Different Substrate Doping Densities (NA)
- **Objective:** Study how varying substrate doping densities affect the C-V characteristics.
- **Parameters:** Use 4 different substrate doping densities.
- **Output:** Plot the C-V characteristics for each doping density.

### 4. VFB vs. Oxide Thickness (tox)
- **Objective:** Analyze the variation of flatband voltage (VFB) with oxide thickness.
- **Parameters:** Use 4 different oxide thicknesses.
- **Output:** Plot VFB vs. tox and extract oxide charge density from the plot.

### 5. Effect of Polysilicon Gate
- **Objective:** Observe the impact of using a highly doped polysilicon gate on C-V characteristics.
- **Parameters:** Use a polysilicon gate of 100 nm thickness.
- **Output:** Analyze the changes in C-V characteristics compared to a metal gate.

## Results

The results section includes all the C-V plots, VTH vs. work function plot, and VFB vs. tox plot generated during the experiments. Extracted values of Cox, VTH, VFB, Qox, and oxide charge density are also provided.

## Comparison

This section presents a comparison table between the calculated and simulated values for all relevant parameters. Discrepancies are discussed in the analysis.

### Observations:
- **Gate Metal Work Function (\(\phi_m\))**: Increasing \(\phi_m\) leads to an increase in both \(V_{FB}\) and \(V_{TH}\).
- **Substrate Doping Density (\(N_A\))**: Increasing \(N_A\) results in a decrease in \(V_{FB}\) and \(V_{TH}\).
- **Oxide Thickness (\(t_{ox}\))**: An increase in \(t_{ox}\) causes \(V_{FB}\) to increase.
- **Polysilicon Gate**: Using a \(p^{+}\) polysilicon gate results in \(V_{FB} \approx 0\) and a significant increase in \(V_{TH}\).

