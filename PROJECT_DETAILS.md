# Detailed Project Documentation

## 1. Project Title

**Design of a CSRR-Loaded Quad-Port Common Patch Configuration Antenna for 5G NR Applications**

## 2. Project Overview

This B.Tech Electronics and Communication Engineering major project investigates a four-port common-patch MIMO antenna enhanced with Complementary Split Ring Resonators (CSRRs). The antenna was designed and simulated in CST Microwave Studio, fabricated as a physical prototype, and evaluated using VNA and anechoic-chamber measurements.

## 3. Objective

- Design a compact quad-port antenna for 5G NR operation around 3.5 GHz.
- Study reflection coefficient, port isolation, VSWR, gain, efficiency, current distribution, and radiation patterns.
- Fabricate the optimized antenna and compare simulated and measured performance.

## 4. Tools and Equipment

- CST Microwave Studio
- Vector Network Analyzer (VNA)
- Anechoic chamber
- RF measurement cables and connectors
- PCB fabrication process

## 5. Design and Simulation Workflow

1. Define the substrate and conducting materials.
2. Create the common radiating patch and four feed ports.
3. Introduce the rectangular slots and CSRR structures.
4. Configure boundaries, ports, and the frequency sweep in CST.
5. Simulate the S-parameters and inspect impedance matching and port isolation.
6. Analyze gain, efficiency, surface current, and radiation patterns.
7. Optimize the geometry for the target 3.5 GHz band.
8. Fabricate the final design and perform experimental validation.

## 6. Key Results

| Parameter | Observed result |
|---|---:|
| Target operating frequency | 3.5 GHz |
| Simulated reflection coefficient (S11) | Approximately -35 dB |
| Maximum simulated gain | Approximately 6.59 dBi |
| Maximum surface current | Approximately 179 A/m |

### Reflection Coefficient

The simulated reflection coefficient indicates resonance near the target 3.5 GHz frequency and good impedance matching.

![Reflection coefficient S11](images/s11-reflection-coefficient.jpeg)

### Antenna Gain

The simulated 3D gain pattern shows a maximum gain of approximately 6.59 dBi at 3.5 GHz.

![Antenna gain at 3.5 GHz](images/gain-qcpc-3.5ghz.jpeg)

### Surface Current Distribution

The current distribution highlights the electromagnetic interaction among the common patch, feed regions, slots, and CSRR-loaded structure.

![Surface current distribution](images/surface-current-distribution-3.5ghz.jpeg)

### Radiation Characteristics

Co-polarization and cross-polarization plots were used to compare the simulated and measured radiation characteristics.

![Simulated and measured radiation patterns](images/radiation-patterns-3.5ghz.jpeg)

## 7. Fabrication

The optimized antenna was fabricated for experimental validation.

| Front view | Back view |
|---|---|
| ![Fabricated antenna front view](images/fabricated-antenna-front.jpg) | ![Fabricated antenna back view](images/fabricated-antenna-back.jpg) |

## 8. Experimental Measurement

The fabricated prototype was evaluated using a Vector Network Analyzer for S-parameter measurements and an anechoic chamber for radiation-pattern testing.

| VNA setup | Anechoic-chamber setup |
|---|---|
| ![VNA measurement setup](images/vna-measurement.jpg) | ![Anechoic chamber setup](images/anechoic-chamber-setup.jpg) |

## 9. IEEE Publication

This research was published on IEEE Xplore:

**Design of a CSRR-Loaded Quad-Port Common Patch Configuration Antenna for 5G NR Applications**

[View the publication on IEEE Xplore](https://ieeexplore.ieee.org/document/11663631)

## 10. Author

**Kasukurthi Vishnu Vardhan**  
B.Tech, Electronics and Communication Engineering  
Vignan's Lara Institute of Technology and Science
