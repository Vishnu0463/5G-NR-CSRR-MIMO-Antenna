# Project Details

## CSRR-Loaded Quad-Port Common Patch Antenna for 5G NR Applications

## 1. Project Overview

This project presents the design, simulation, fabrication, and experimental analysis of a CSRR-loaded quad-port common patch antenna intended for 5G NR applications.

The antenna structure was designed and analyzed using CST Microwave Studio. The proposed configuration uses a common radiating patch with four feeding ports and Complementary Split Ring Resonator (CSRR) structures to obtain the required antenna characteristics.

The antenna performance was evaluated using reflection coefficient, radiation characteristics, gain, surface current distribution, and experimental measurements.

---

## 2. Project Objective

The main objectives of this project are:

- Design a compact antenna suitable for 5G NR applications.
- Implement a quad-port antenna configuration.
- Incorporate CSRR structures into the antenna design.
- Analyze impedance matching and reflection coefficient.
- Study the surface current distribution.
- Analyze antenna gain and radiation characteristics.
- Fabricate the proposed antenna prototype.
- Validate the antenna experimentally using measurement equipment.
- Compare simulated and measured antenna performance.

---

## 3. Software and Technologies

The project involves:

- CST Microwave Studio
- RF and Microwave Engineering
- Antenna Design
- Electromagnetic Simulation
- MIMO / Multi-Port Antenna Concepts
- Complementary Split Ring Resonator (CSRR)
- Vector Network Analyzer (VNA)
- Anechoic Chamber Measurements
- 5G NR Communication

---

## 4. Antenna Configuration

The proposed antenna consists of a common radiating patch with four feeding ports.

The four-port configuration is used to provide a multi-port antenna structure suitable for modern wireless communication systems.

Complementary Split Ring Resonator (CSRR) structures are incorporated into the antenna geometry to modify the electromagnetic behavior of the antenna and achieve the desired operating characteristics.

---

## 5. Design and Simulation Methodology

The antenna was modeled and analyzed using CST Microwave Studio.

The general workflow followed in this project was:

1. Design the initial antenna geometry.
2. Define the substrate and conducting materials.
3. Create the common radiating patch.
4. Configure the four antenna ports.
5. Introduce CSRR structures.
6. Perform electromagnetic simulation.
7. Analyze the reflection coefficient.
8. Examine the surface current distribution.
9. Analyze antenna gain.
10. Study the radiation characteristics.
11. Optimize the antenna configuration.
12. Fabricate the final antenna.
13. Perform experimental measurements.
14. Compare simulation and measurement results.

---

## 6. Reflection Coefficient

The reflection coefficient was analyzed to evaluate impedance matching and identify the operating region of the antenna.

The S-parameter characteristics provide important information about the antenna's resonant behavior and matching performance.

The corresponding result is available in:

`images/s11-reflection-coefficient.jpeg`

---

## 7. Antenna Gain

The three-dimensional gain pattern was analyzed using CST Microwave Studio to study the radiation performance of the antenna.

The corresponding gain result is available in:

`images/gain-qcpc-3.5ghz.jpeg`

---

## 8. Surface Current Distribution

Surface current distribution was analyzed to understand how electromagnetic current is distributed across the proposed antenna structure.

This analysis is useful for studying the contribution of different portions of the antenna and the CSRR-loaded structure to the overall antenna behavior.

The corresponding result is available in:

`images/surface-current-distribution-3.5ghz.jpeg`

---

## 9. Radiation Characteristics

The radiation characteristics of the proposed antenna were analyzed through radiation-pattern results.

Simulated and measured radiation characteristics were considered as part of the antenna performance evaluation.

The corresponding result is available in:

`images/radiation-patterns-3.5ghz.jpeg`

---

## 10. Fabrication

After completing the simulation and optimization stages, the proposed antenna was fabricated for experimental validation.

### Fabricated Antenna – Front View

![Fabricated Antenna Front View](images/fabricated-antenna-front.jpg)

### Fabricated Antenna – Back View

![Fabricated Antenna Back View](images/fabricated-antenna-back.jpg)

---

## 11. Experimental Measurement

Experimental measurements were performed on the fabricated antenna.

A Vector Network Analyzer (VNA) was used for antenna measurement, while the radiation measurement setup included an anechoic chamber.

### VNA Measurement Setup

![VNA Measurement Setup](images/vna-measurment.jpg)

### Anechoic Chamber Measurement Setup

![Anechoic Chamber Measurement Setup](images/anechoic-chamber-setup.jpg)

---

## 12. Simulation and Experimental Validation

The final stage of the project involved evaluating the simulated antenna results together with experimental measurements from the fabricated prototype.

This validation helps demonstrate the practical performance of the proposed CSRR-loaded quad-port antenna configuration.

---

## 13. Applications

The proposed antenna is intended for applications including:

- 5G NR wireless communication
- Multi-port antenna systems
- MIMO communication systems
- RF and microwave applications

---

## 14. IEEE Publication

This project work is associated with an IEEE publication.

**Title:** Design of a CSRR-Loaded Quad-Port Common Patch Configuration Antenna for 5G NR Applications

**IEEE Xplore:**  
https://ieeexplore.ieee.org/document/11663631

---

## 15. Author

**Kasukurthi Vishnu Vardhan**  
B.Tech – Electronics and Communication Engineering  
Vignan's Lara Institute of Technology and Science

---

## Repository Structure

```text
5G-NR-CSRR-MIMO-Antenna/
│
├── README.md
├── PROJECT_DETAILS.md
│
└── images/
    ├── fabricated-antenna-front.jpg
    ├── fabricated-antenna-back.jpg
    ├── vna-measurement.jpg
    ├── anechoic-chamber-setup.jpg
    ├── s11-reflection-coefficient.jpeg
    ├── gain-qcpc-3.5ghz.jpeg
    ├── surface-current-distribution-3.5ghz.jpeg
    └── radiation-patterns-3.5ghz.jpeg
