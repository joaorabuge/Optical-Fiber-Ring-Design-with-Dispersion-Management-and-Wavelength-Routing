# Optical Fiber Ring Design with Dispersion Management and Wavelength Routing

## Project Overview

This project, part of the **Telecommunications and Computer Engineering** course at ISCTE-IUL, focuses on designing an optical ring with dispersion management and wavelength routing. The primary goal is to assess the feasibility of a unidirectional optical fiber ring with path protection, wavelength routing, and dispersion management capabilities.

### Objectives

- Evaluate the feasibility of a unidirectional fiber optic ring.
- Ensure path protection, wavelength routing, and dispersion management.
- Guarantee the optical ring's capacity to handle:
  - `X Gbit/s` per optical channel (based on group assignment)
  - `Y Gbit/s` total capacity (based on group assignment)

### Project Requirements

The optical ring design involves:

1. Using identical emitters, receivers, and reconfigurable optical add-drop multiplexers (ROADMs) for all WDM channels and ring nodes.
2. Implementing dispersion compensating modules (DCMs) in sections where required.
3. Evaluating different scenarios, such as single-channel and multi-channel operations, to decide on the need for dispersion compensation.

## Project Parts

### Part I: Single-Channel Operation

- **Objective**: Analyze the need for dispersion compensation.
- **Parameters**:
  - Use of the fiber optic Corning SMF-28e+.
  - Wavelength: 1554.13 nm
  - Emitter A and Receiver A

### Part II: Multi-Channel Operation

- **Objective**: Generalize Part I's analysis to multi-channel scenarios.
- **Components Selection**: Emitters, receivers, optical amplifiers, and DCMs.

## Methodology

1. **Identification of Optical Links**: Select the longest links for analysis to ensure robust performance.
2. **Dispersion Management**: Determine the need for dispersion compensation based on the maximum allowable residual dispersion.
3. **Component Selection**: Choose the most cost-effective and efficient components (emitters, receivers, amplifiers, multiplexers, etc.) for each scenario.
4. **Amplification Strategies**: Evaluate the use of pre-, post-, and line amplifiers.

## Tools and Resources

- **Fiber Type**: Corning SMF-28e+
- **Dispersion Compensation Modules**: DCMs as specified in project guidelines.
- **Optical Amplifiers**: Selected based on gain requirements from provided datasheets.
- **Multiplexers/Demultiplexers**: AWG-based WDM devices.
- **Software**: MATLAB or equivalent for simulation and analysis.

## Deliverables

1. **Part I Report**: Analysis of single-channel operation and dispersion management needs.
2. **Part II Report**: Comprehensive multi-channel operation report, including full component selection and design validation.
3. **Simulation Data**: MATLAB scripts or equivalent used for calculations and design validation.


## Academic Year

2022/2023

