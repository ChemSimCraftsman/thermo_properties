# Thermodynamic Properties vs Timestep

This repository contains Python code for analyzing and visualizing **thermodynamic properties** (energy, pressure, temperature, etc.) as a function of simulation timestep.  

The notebook (`thermo_property vs timestep.ipynb`) provides tools to read LAMMPS log/dump data, extract relevant columns, and generate plots to understand the time evolution of system properties during molecular dynamics (MD) simulations.

---

## 📌 About the Project
In molecular dynamics, thermodynamic quantities fluctuate but approach equilibrium averages.  
This notebook helps:
- Parse simulation outputs
- Plot energy, temperature, and other quantities vs time
- Detect equilibrium and transient regions
- Export clean plots for publications

---

## ⚙️ System / Environment
The code has been tested on the following system:
- **OS:** Linux (Ubuntu 22.04 LTS)  
- **Python:** 3.10+  
- **Core packages:** NumPy, Pandas, Matplotlib  

---

## 📦 Requirements
Install the required Python packages:

```bash
pip install numpy pandas matplotlib
