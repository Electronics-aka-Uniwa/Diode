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

<hr>

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Panagiotis Giannakopoulos, Professor
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/panagiotis-yannakopoulos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/panos-yannakopoulos-b9b6987/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Academic Scholar
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/academic_sc_ho/" target="_blank">UNIWA Profile</a> ·
  <a href="https://scholar.google.com/citations?user=-LnaZGgAAAAJ&hl=en" target="_blank">Scholar</a>
</p>

<p align="center">
  Co-supervisor: Michalis Diamantopoulos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/22674/" target="_blank">UNIWA Profile</a>
</p>

</hr>

---

<p align="center">
  Athens, November 2022
</p>

---

<p align="center">
  <img src="https://www.autodesk.com/products/fusion-360/blog/wp-content/uploads/2024/02/Current_Flow_DIODE_Smaller_AdobeStock_250989093-1024x522.jpg" width="250"/>
</p>

---

# INSTALL

## Diode

This guide explains how to install, set up, and use the **Diode** laboratory project.  
The repository contains **theoretical material**, **Multisim simulations**, **experimental results**, and **diagrams** related to **silicon crystal diodes** and **Zener diodes**.

---

## 1. Prerequisites

Before working with this project, ensure the following requirements are met.

---

## 2. Software Requirements

### 2.1 NI Multisim

- **NI Multisim 14 or newer**
- Required to open and run circuit simulations and verify diode behavior.
- Used extensively in:
  - Forward-biased diode experiments
  - Reverse-biased diode experiments
  - Zener diode analysis

### 2.2 PDF Reader

- Any modern PDF viewer (Adobe Reader, browser-based, etc.)
- Required to open:
  - Assignment descriptions
  - Theoretical documentation (English & Greek)

### 2.3 Diagram Viewer

- **Microsoft Visio** or a compatible viewer
- Required for `.vsdx` files (e.g., `zener/Q4.vsdx`)

---

## 3. Hardware Requirements (Optional – for Physical Lab Work)

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

## 4. Installation & Setup

### 4.1 Clone the Repository

```bash
git clone https://github.com/Electronics-aka-Uniwa/Diode.git
cd Diode
```

### 4.2 Open and Run Multisim Simulations

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

### 4.3 Access Theoretical Documentation

Open the files located in the `docs/` directory:

- English: `Diode.pdf`
- Greek: `Δίοδος.pdf`

These documents cover:

- PN-junction theory
- Forward and reverse bias operation
- Zener diode breakdown behavior

### 4.4 Review Assignment Instructions

Navigate to the `assign/` folder:

- English: `Exercise-3rd-Diode.pdf`
- Greek: `Άσκηση-3η-Δίοδος.pdf`

Follow these documents for:

- Required experiments
- Measurement procedures
- Expected analysis and conclusions

### 4.5 View Diagrams and Graphs

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

## 5. Running the Experiments

### 5.1 Silicon Crystal Diode

- Forward Bias
  - Measure voltage and current
  - Observe barrier potential (~0.6 V)
- Reverse Bias
  - Confirm minimal current flow
  - Verify theoretical expectations

### 5.2 Zener Diode

- Forward Bias
  - Analyze conduction characteristics
    -Reverse Bias
  - Observe breakdown region
  - Verify voltage stabilization behavior
