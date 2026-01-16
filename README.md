<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Electronics</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  Diode
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Eleni Tsalera, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.researchgate.net/profile/Eleni-Tsalera-2" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Co-supervisor: Michalis Diamantopoulos, Lecturer in Applications
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/22674/" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, November 2022
</p>

---

# Project Overview

This project was completed for the **Department of Information and Computer Engineering** at the **University of West Attica (UNIWA)**. It examines the electrical characteristics and operating behavior of **silicon crystal diodes** and **Zener diodes** under different biasing conditions.

The analysis is conducted through:
- **Theoretical calculations**
- **Software simulations**
- **Experimental laboratory measurements**

---

## Table of Contents

| Section | Folder / File | Description |
|--------:|---------------|-------------|
| 1 | `assign/` | Assignment material |
| 1.1 | `assign/Exercise-3rd-Diode.pdf` | Assignment description (English) |
| 1.2 | `assign/Άσκηση-3η-Δίοδος.pdf` | Assignment description (Greek) |
| 2 | `components/` | Lab components and equipment images |
| 3 | `diode/ForwardDiode/ForwardDiodeGe/` | Forward-biased Germanium diode experiments |
| 3.1 | `diode/ForwardDiode/ForwardDiodeSi/` | Forward-biased Silicon diode experiments |
| 3.2 | `diode/Graphs/` | Graphical results of diode experiments |
| 3.3 | `diode/Lab5/` | Lab 5 experimental data and drawings |
| 3.4 | `diode/NonForwardDiode/NonForwardDiodeGe/` | Reverse-biased Germanium diode experiments |
| 3.5 | `diode/NonForwardDiode/NonForwardDiodeSi/` | Reverse-biased Silicon diode experiments |
| 3.6 | `diode/Q5/` | Question 5 experiments and results |
| 3.7 | `diode/Q6/` | Question 6 experiments and results |
| 4 | `docs/` | Theoretical documentation |
| 4.1 | `docs/Diode.pdf` | Diode theory (English) |
| 4.2 | `docs/Δίοδος.pdf` | Diode theory (Greek) |
| 5 | `zener/ForwardZener/` | Forward-biased Zener diode experiments |
| 5.1 | `zener/Graphs/` | Graphical results for Zener diode |
| 5.2 | `zener/NonForwardZener/` | Reverse-biased Zener diode experiments |
| 5.3 | `zener/Q4.vsdx` | Question 4 drawings and diagrams |
| 6 | `README.md` | Repository overview and instructions |

---

## Technical Contents

The project is divided into two main sections:

### 1. Crystal Diode (Silicon)

A detailed study of a silicon crystal diode, including:

- **Forward Bias**  
  - Theoretical analysis  
  - Simulation using **Multisim**  
  - Experimental laboratory measurements  

- **Inverse Bias**  
  - Examination of reverse-biased diode behavior  

- **Key Findings**  
  - Observation of the **barrier potential** stabilizing at approximately **0.6 V**  
  - Experimental verification of **Ohm’s Law** and **Kirchhoff’s Laws**

---

### 2. Zener Diode

An investigation into the behavior of Zener diodes, focusing on:

- **Forward Bias**  
  - Analysis of forward conduction characteristics  

- **Inverse Bias**  
  - Study of **reverse breakdown** behavior  
  - Voltage stabilization properties of the Zener diode  

---

## Equipment Used

The following equipment and components were used during laboratory experimentation:

- **DC Power Supply** – Provides variable input voltage  
- **MCP MT8045 Multimeter** – Digital and analog measurements  
- **M21-7000A Training System** – Includes breadboard for circuit assembly  
- **Components**  
  - Resistors: **4.7 kΩ**, **150 Ω**  
  - **Silicon diodes**  
  - **Zener diodes**

---

## Software Tools

- **Multisim** – Simulation and verification of circuit behavior  
- **MS Visio** – Creation of schematic diagrams for diode polarizations

---

# Installation & Setup Guide  

This guide explains how to install, set up, and use the **Diode** laboratory project.  
The repository contains **theoretical material**, **Multisim simulations**, **experimental results**, and **diagrams** related to **silicon crystal diodes** and **Zener diodes**.

---

## Prerequisites

Before working with this project, ensure the following requirements are met.

---

### 1. Software Requirements

#### NI Multisim
- **NI Multisim 14 or newer**
- Required to open and run circuit simulations and verify diode behavior.
- Used extensively in:
  - Forward-biased diode experiments
  - Reverse-biased diode experiments
  - Zener diode analysis

#### PDF Reader
- Any modern PDF viewer (Adobe Reader, browser-based, etc.)
- Required to open:
  - Assignment descriptions
  - Theoretical documentation (English & Greek)

#### Diagram Viewer (Optional)
- **Microsoft Visio** or a compatible viewer
- Required for `.vsdx` files (e.g., `zener/Q4.vsdx`)

---

### 2. Hardware Requirements (Optional – for Physical Lab Work)

If performing **real laboratory measurements**, the following equipment is required:

- **DC Power Supply**
- **Digital Multimeter:** MCP MT8045
- **Training System:** M21-7000A (with breadboard)
- **Components**
  - Resistors: **4.7 kΩ**, **150 Ω**
  - **Silicon diodes**
  - **Zener diodes**

> Hardware is **not required** if you are only running simulations and reviewing documentation.

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Electronics-aka-Uniwa/Diode.git
cd Diode
```

### 2. Open and Run Multisim Simulations
- Launch NI Multisim.
- Navigate to the relevant experiment folder, for example:
```bash
diode/ForwardDiode/ForwardDiodeSi/
```
- Open the provided Multisim project files.
- Click Run Simulation.
- Observe:
  - Diode I–V characteristics
  - Forward voltage drop
  - Reverse-bias behavior
  - Zener breakdown region

### 3. Access Theoretical Documentation
Open the files located in the `docs/` directory:
- English: `Diode.pdf`
- Greek: `Δίοδος.pdf`

These documents cover:
- PN-junction theory
- Forward and reverse bias operation
- Zener diode breakdown behavior

### 4. Review Assignment Instructions
Navigate to the `assign/` folder:
- English: `Exercise-3rd-Diode.pdf`
- Greek: `Άσκηση-3η-Δίοδος.pdf`

Follow these documents for:
- Required experiments
- Measurement procedures
- Expected analysis and conclusions

### 5. Optional: View Diagrams and Graphs
- Open experimental graphs from:
```bash
diode/Graphs/
zener/Graphs/
```
- Open Visio drawings (if available) using Microsoft Visio:
```bash
zener/Q4.vsdx
```

---

## Running the Experiments
### 1. Silicon Crystal Diode
- Forward Bias
  - Measure voltage and current
  - Observe barrier potential (~0.6 V)
- Reverse Bias
  - Confirm minimal current flow
  - Verify theoretical expectations

### 2. Zener Diode
- Forward Bias
  - Analyze conduction characteristics
-Reverse Bias
  - Observe breakdown region
  - Verify voltage stabilization behavior
