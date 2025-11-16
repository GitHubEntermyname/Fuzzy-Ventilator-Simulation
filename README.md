# 🫁 Fuzzy Logic Controlled Medical Ventilator Simulation

### 📌 Overview
This project models a **positive-pressure medical ventilator system** using **MATLAB/Simulink**, integrated with a **fuzzy logic controller**.  
The ventilator simulates adaptive regulation of air pressure, tidal volume, breathing frequency, and humidification — mimicking real-time clinical ventilation.

---

### 🧠 Core Modules
- **Flow Generation** → Supplies preset airflow to simulate tidal volume  
- **Lung Model** → Translational Mechanical Converter (MA) block simulating elastance and resistance  
- **Fuzzy Logic Controller** → Adjusts tidal volume, frequency, and PEEP based on pressure/flow feedback  
- **Humidifier Subsystem** → Conditions air with controlled temperature and humidity  
- **Graphical Monitoring** → Real-time scopes for pressure, humidity, temperature, and flow rate  

---

### 🛠️ Technical Highlights
- Displacement → Lung Volume  
- Force → Airway Pressure  
- Spring Constant → Respiratory Elastance  
- Damping Coefficient → Respiratory Resistance  
- Fuzzy Inputs: Pressure, Flow  
- Fuzzy Outputs: Tidal Volume, Frequency, PEEP  
- Gas exchange (O₂/CO₂) not modeled — modular for future expansion  

-
---

### 📚 Publications
This work is documented in detail in the following paper:

- Danish Abdullah, *Modeling and Simulation of a Fuzzy Logic Controlled Medical Ventilator Using MATLAB/Simulink*, Zenodo (2025).  
  DOI: [10.5281/zenodo.17503822](https://doi.org/10.5281/zenodo.17503822)

---

### 📸 Visual Outputs
- Pressure-volume loop  
- Lung inflation waveform  
- Humidity and temperature profiles  
- Control signal timing and valve actuation  

---

### 📚 Requirements
- MATLAB R2021b or later  
- Simulink  
- Fuzzy Logic Toolbox  
- Simscape (for Translational Mechanical Converter block)

---

### 🙌 Acknowledgment
Developed by **Danish Abdullah**, Department of Mechatronics Engineering, Air University Islamabad.  
This simulation contributes to intelligent ventilator design and adaptive control research in biomedical engineering.
