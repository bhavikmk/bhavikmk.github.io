---
layout: post
title:  Steam Turbine Performance
categories: [Engineering]
excerpt: Engineering Notes for Monitoring of Steam Turbine Performance
---

# Steam Turbine Performance

### Performance Monitoring

- Monitor Plant Heat balance and Individual Equipment Heat balance
- Plant Thermodynamic Cycle
- Parameters
    - Steam Inlet Pressure, Temperature, Flow
    - Feed water Flow, Temp
    - Cooling Water inlet and Outlet Temperature
    - Condenser Pressure
    - Generator Power & Power Factor

### Condition Monitoring

- Mechanical Parameters
    - **Vibrations**
        - **Radial** (2 Proximity Probes in Orthogonal config;  Shutdown parameter
        - **Axial (**2 Proximity Probe within thrust bearing)   Shutdown parameter
        - **Speed\Phase angle** : Key-phasor transducer (once per turn signal for determining vibration phase and shaft rotative speed)
        - Casing Vibrations: seismic transducers on radial bearing housings ****
        - **Shaft Eccentricity:** measure residual shaft bow under gravity sag
        - Excessive Bearing to Shaft Clearance
        - Support structure looseness
    - **Oil Quality**
        - Contamination
        - Shaft Scoring
        - Babbitt Material Loss
    - Temperature Monitoring
        - Bearing Babbitt Temperature
        - Bearing Housing or Shell Temp
    - **What Else parameters Reflect condition?**

### Why Monitoring apart from Machinery Protection

- Planning Shutdown
- Inventory Management
- Transition to predictive maintenance from preventive maintenance

### Condition Monitoring of Lube Oil

- Pressure distribution on lube oil film of a journal bearing
- **Degradation Mechanisms**
    - **Oxidation**: Presence of oxygen reacts with oil and form **carboxylic acids.** Temp is critical factor (rate doubles with rise in 10 `C)
    - **Thermal Degradation:** Breakdown of Oil molecules by heat forming insoluble compounds (soft contaminants).

### Tests for carried out to assess the condition of oil (ASTM, IP, DIN)

- Kinematic Viscosity,
- Water,
- Insoluble particulates (What is particulates)
- Acid number ?, Neutralization number
- Ferrography, Rust
- Foam, Air release,
- Cleanliness code

## Alarm level for turbine

**Vibration data (from 1→ n)**

***Limit = Mean + 4*Standard Deviation***

## Instruments

- **Motion (Vibration, Rotor Eccentricity)**
    - Eddy Current or Proximity Probes
    - Velocity Transducers
    - Shaft riders
    - accelerometers
- **Position (Wear, Rotor position, Casing Expansion, Differential Expansion, CV Position)**
    - Eddy Current
    - LVDT
    - Linear Rotory Potentiometers
- **Speed (and Acceleration, Over Speed detection**
    - Active or Passive Eddy Current Probes
- **Process (Bearing White Metal or Babbitt Temp, Shell diff. temp, Lube oil)**
    - Thermocouples or
    - RTD
    - **Oil Pressure** : Piezoelectric Strain gauge pressure transducers

## Study

- Pressure distribution and principle of journal bearing
