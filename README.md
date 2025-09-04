# BEV-simulation-for-optimum-motor-and-gear-ratio-configuration
This MATLAB project focuses on optimizing traction motor configurations and gear ratios for electric vehicles. The simulation framework evaluates different motor-gear combinations to identify the optimum setup based on minimum energy consumption
# EV Motor-Gear Optimization Model

This project provides a MATLAB-based simulation framework that uses an **FMU block** to test three traction motor configurations with varying gear ratios. The gear ratio is swept from **5.0 to 15.0** in steps of **0.5**, and the framework determines the optimum motor-gear combination based on **minimum energy consumption** while satisfying performance targets.

---

## 🚗 Overview
Electric vehicle performance and efficiency are highly influenced by the motor-gear ratio combination. Selecting the right setup is essential for balancing:
- Energy consumption  
- Vehicle dynamics (acceleration, gradeability)  
- Top speed capability  

This model simulates multiple motor configurations through an FMU block and evaluates gear ratio variations to find the **most energy-efficient solution**.

---

## ⚙️ Features
- Three predefined motor configurations via FMU block  
- Gear ratio sweep from 5 to 15 in 0.5 increments  
- Drive cycle–based energy consumption analysis  
- Comparative results for different configurations  
- Visual plots for torque, power, and efficiency  

---

## 📊 Methodology
1. Import FMU block containing three motor models.  
2. Define gear ratio range (5.0 → 15.0, step = 0.5).  
3. Run simulations over a chosen drive cycle.  
4. Calculate and compare total energy consumption.  
5. Identify the optimum motor-gear combination.  

---

## 📈 Results
The model generates:  
- Energy consumption vs. gear ratio plots  
- Comparison across three motor configurations  
- Torque–speed and power curves  
- Best configuration minimizing total energy usage  

---

## ▶️ How to Run
1. Clone the repository.  
2. Open MATLAB/Simulink and load the FMU-based model.  
3. Run the main script (`Technical_Test_2_script.mlx`).  
4. Wait for the simulation to run.  
5. Review results through plots and exported data.  

---

## 🔮 Future Scope
- Extend FMU to support additional motor types.  
- Test with multiple drive cycles (WLTP, FTP-75, custom).  
- Add battery sizing and state-of-charge modeling.  
- Implement multi-objective optimization (energy + performance + cost).  
