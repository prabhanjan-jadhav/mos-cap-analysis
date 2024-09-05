# C-V Characteristics of MOS Capacitor

This repository contains the simulation and analysis of the C-V characteristics of a MOS capacitor using Scaps software. The project was part of **EE313: Microelectronics Laboratory** course.

## Overview

This project analyzes the capacitance-voltage (C-V) characteristics of a MOS capacitor using the Scaps software. The analysis covers the effects of varying gate voltage, gate metal work function, substrate doping density, and oxide thickness on the C-V characteristics.

## Project Structure

- **report.pdf**: Detailed analysis report, including theoretical equations, results, and conclusions.
- **results.pdf**: Contains all the simulation plots and data.
- **moscap_data/**: Contains moscap configuration and data of all simulations with different parameters.

## Simulation Tasks

The following tasks were performed using the Scaps software:

a) **Gate Voltage Variation**: 
   - Simulated the C-V characteristics by varying the gate voltage between -2V and 2V.
   - Extracted values of \(C_{ox}\), \(V_{TH}\), \(V_{FB}\), and \(Q_{ox}\) from the C-V plot.

b) **Gate Metal Work Function**:
   - Used 4 different metals for the gate and plotted the variation of \(V_{TH}\) vs. gate metal work function.

c) **Substrate Doping Density (NA)**:
   - Analyzed the C-V characteristics with 4 different substrate doping densities.

d) **Oxide Thickness (tox)**:
   - Varied the oxide thickness and obtained \(V_{FB}\) values.
   - Extracted the oxide charge density from the \(V_{FB}\) vs. \(t_{ox}\) plot.

e) **Polysilicon Gate**:
   - Replaced the metal gate with a highly doped polysilicon gate of thickness 100 nm and observed changes in the C-V characteristics.

## Report and Results

- **Detailed Report**: The full analysis, including equations and conclusions, is provided in `report.pdf`.
- **Simulation Plots**: All plots generated during the simulations are compiled in `results.pdf`.

## Conclusion

The simulation results are consistent with theoretical predictions, demonstrating the impact of gate metal work function, substrate doping density, and oxide thickness on the C-V characteristics of MOS capacitors.
