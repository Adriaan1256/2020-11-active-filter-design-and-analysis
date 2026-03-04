# Active Filter Design & Frequency Response Analysis

Undergraduate Signals & Systems Project  
University of Pretoria  
Completed: March 2020  

---

## 📌 Overview

This project involved the analytical design, simulation, and validation of three active analogue filters:

- Chebyshev Low-Pass Filter
- Butterworth High-Pass Filter
- Minimal-Ripple Band-Pass Filter

Each filter was designed from first principles using transfer function theory, implemented using active op-amp topologies, and validated using LTSpice simulations. Frequency response characteristics were plotted and analysed using Python.

---

## 🎯 Objectives

- Design a 3rd-order Chebyshev low-pass filter (4 kHz cutoff, 1 dB ripple, 60 dB/decade roll-off)
- Design a 3rd-order Butterworth high-pass filter (8 kHz cutoff, 60 dB/decade roll-off)
- Design a 2nd-order minimal-ripple band-pass filter (8 kHz – 80 kHz passband)
- Derive transfer functions H(s), H(jω), and H(f)
- Analyse magnitude and phase response
- Select real component values (R, C) based on specifications
- Validate theoretical models using LTSpice simulations
- Compare simulated and analytical results

---

## 🛠 Tools & Technologies Used

- Python
- NumPy
- Matplotlib
- LTSpice
- Laplace Transform theory
- Frequency-domain analysis
- Active op-amp filter topology design

---

## 🔬 Filters Designed

### 1️⃣ Chebyshev Low-Pass Filter
- Cutoff frequency: 4 kHz
- Passband ripple: 1 dB
- Roll-off: 60 dB/decade
- Demonstrates trade-off between ripple and roll-off speed

### 2️⃣ Butterworth High-Pass Filter
- Cutoff frequency: 8 kHz
- Monotonic magnitude response (no ripple)
- 60 dB/decade roll-off
- Demonstrates maximally flat response characteristics

### 3️⃣ Minimal-Ripple Band-Pass Filter
- Passband: 8 kHz – 80 kHz
- 40 dB/decade roll-off
- Designed using active inverting op-amp topology
- Demonstrates band-pass synthesis and Q-factor control

---

## 📊 Engineering Concepts Demonstrated

- Transfer function derivation
- Normalised frequency transformation
- Filter order determination
- Q-factor analysis
- Gain configuration for stability
- Ripple vs roll-off trade-offs
- Cascading filter behaviour
- Frequency sweep validation

---

## 📄 Project Documentation & Code

The full report including:

- Mathematical derivations
- Circuit diagrams
- LTSpice simulation results
- Python plotting scripts (Appendix A)

is available here:

👉 **[View Full Project Report (PDF)](docs/ELI220_Practical_Assignment_3.pdf)**

All Python code used to generate frequency response plots is included in the appendix of the report.

---

## 💡 Engineering Significance

This project demonstrates applied analogue signal processing and filter synthesis — foundational skills for:

- Communications systems
- Embedded electronics
- Control systems
- Audio and RF engineering
- Signal conditioning in data acquisition systems
