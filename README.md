# PSPICE-Based Circuit Analysis Project (ENEE2304)

This project presents a series of electrical circuit analyses using **PSPICE simulations**. The work includes applications of the **Superposition Theorem**, **Thevenin's Theorem**, **Maximum Power Transfer**, **Sinusoidal Steady-State Response**, and both **First and Second Order Circuit Transient Analyses**.


---

## 🧾 Contents

### 🔧 Question 1: Superposition Theorem
- Computed voltage and current across **R3** using:
  - Full-circuit solution
  - Individual source contributions (V1 and V2)
- Verified the superposition principle by comparing results

### 🧲 Question 2: Thevenin's Theorem & Maximum Power Transfer
- Measured voltage/current on **RL**
- Plotted power vs. resistance using DC sweep
- Computed **R<sub>Thevenin</sub>** via:
  - Open-circuit voltage
  - Short-circuit current
- Simulated Thevenin equivalent circuit
- Compared results for validation

### 🔁 Question 3: Sinusoidal Steady-State Analysis
- Plotted input voltage **Vin(t)** and resistor voltage **VR(t)**
- Calculated **phase shift (Δθ)** based on time difference
- Repeated for an RC and RL circuit
- Discussed behavior and phase relationships

### ⚡ Question 4: First Order RC Circuit
- Simulated **charging behavior of a capacitor**
- Plotted **VI(t)** and **VC(t)**
- Calculated and verified **time constant (τ)** both theoretically and from graph

### 🎯 Question 5: Second Order RLC Circuit
- Plotted **Vi(t)** and **VC(t)** for different resistance values:
  - R = 10kΩ (Overdamped)
  - R = 3.162kΩ (Critically damped)
  - R = 500Ω (Underdamped)
- Observed and explained damping behavior

---

## 📊 Tools Used
- **OrCAD / PSPICE Simulation Suite**
- Voltage/current probes
- Time-domain and frequency-domain sweep
- Graph plotting tools

---

## 📈 Sample Graphs and Insights
- Superposition validation: Matching combined result with full circuit output
- RL Power Curve: Peak at **R<sub>Thevenin</sub> ≈ 987.35Ω**
- Sinusoidal shift: Phase shifts ~89° in both RL and RC
- Transients: Confirmed τ for RC and observed damping effects in RLC


---

## 📌 Learning Outcomes
- Apply and validate core circuit theorems using simulation
- Use PSPICE to visualize and measure electrical behavior
- Interpret phase and transient responses in time and frequency domains
- Design and analyze circuits using practical techniques

---

## 📜 License
This project is submitted as part of Birzeit University's ENEE2304 coursework and is intended for educational use only.



