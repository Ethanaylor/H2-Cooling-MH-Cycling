# H2-Cooling-MH-Cycling
# Hydrogen-Powered Cooling: Metal Hydride Cycling Rig

This repository documents the development and analysis of a lab-scale cycling rig used to evaluate metal hydride systems for dual-use hydrogen storage and thermal cooling. The project is part of a broader effort to decarbonise the UK cold chain using hydrogen fuel cell technologies.

Hydralloy C5 was used as the hydrogen-absorbing material, cycled under sub-zero and ambient conditions using a custom-built system that integrates National Instruments hardware (cDAQ), LabVIEW automation, and temperature control via a PRA Panel.

---

## 🔧 System Overview

- **Metal Hydride**: Hydralloy C5, loaded in 316L stainless steel sample cylinders
- **Cycling Control**: ERA Demonstrator gas manifold with Swagelok fittings and actuated valves
- **Temperature Regulation**: PRA Panel recirculating bath, –30°C to +200°C, ±1 K stability
- **Instrumentation**:  
  - Bronkhorst Mass Flow Controller (0–25 mlₙ/min)  
  - Pressure transducers (PT1–PT4)  
  - K-type thermocouple  
- **DAQ**: LabVIEW VI “Solid State H₂ Storage” sampling at 1 Hz via NI cDAQ

---

## 📊 Data Features

- Time-stamped logs of pressure, flow, and temperature data across multiple cycles
- Post-processing routines for baseline correction, integration of flow, and plateau pressure estimation
- Kinetic fits and reaction-rate estimation from desorption curves
- Efficiency tracking across repeated absorption/desorption cycles

---

## 📁 Repo Structure



---

## 🧠 AI-Ready Potential

This dataset and system could support various AI applications, including:

- Time-series prediction of hydrogen uptake/desorption
- Real-time system state estimation using incomplete or noisy data
- Predictive maintenance or anomaly detection
- Reinforcement learning for adaptive cycle tuning
- Physics-informed ML to model thermodynamic behaviour

A future extension could involve building a small supervised learning model to estimate plateau pressure or kinetic constants based on partial sensor input.

---

## 🚛 Project Context

This project was conducted as part of a broader research effort to explore clean, efficient alternatives to traditional refrigeration in heavy-duty transport. The final vision is to develop a dual-use hydrogen store capable of powering and cooling refrigerated trucks, reducing emissions and reliance on synthetic refrigerants.

---

## 🧑‍🔬 Author

Developed by Ethan Naylor, Mechanical Engineering @ University of Nottingham\
Interested in AI for energy, hardware-integrated ML, and sustainable systems.

---

## 📬 Contact & Collaborations

For questions, collaboration, or access to full datasets, feel free to reach out via 07401 503 735 or [www.linkedin.com/in/ethan-naylor-a02b1b338](http://www.linkedin.com/in/ethan-naylor-a02b1b338)

---

## 📜 License

MIT License – open for academic and non-commercial use.
