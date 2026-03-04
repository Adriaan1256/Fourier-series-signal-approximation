# Fourier Series Approximation of Periodic Signals  
ELI220 – Practical Assignment 1

## 📌 Overview

This project investigates the analytical derivation and numerical implementation of Fourier Series representations for various periodic signals.

The assignment involved:

- Deriving Fourier coefficients analytically
- Implementing the Fourier expansions in Python
- Plotting signal reconstructions
- Determining the number of harmonics required for accurate approximation

---

## 🎯 Objectives

- Derive Fourier series coefficients for selected periodic functions
- Implement Fourier approximations using Python
- Compare reconstruction accuracy for increasing harmonic counts
- Analyse how signal discontinuities affect convergence

---

## 📡 Signals Analysed

1. Sine wave:  
   x(t) = sin(2πt)

2. Square wave (50% duty cycle)

3. Square wave (10% duty cycle)

4. Sawtooth wave:  
   x(t) = t, 0 ≤ t ≤ 1

---

## 🛠 Tools & Technologies Used

- Python
- NumPy
- Matplotlib
- SciPy (signal module)
- Fourier Series Theory

---

## 📄 Project Documentation & Code

The full project report, including:

- Mathematical derivations
- Explanations
- Plots
- Complete Python source code (Appendix A)

is available here:

👉 **[View Full Project Report (PDF)](ELI220_Practical_Assignment_1.pdf)**

All implementation code is included in Appendix A of the report.

---

## 📊 Key Findings

| Signal | Harmonics Required for Good Approximation |
|--------|-------------------------------------------|
| Sine wave | 1 component |
| Square wave (50%) | ~40 components |
| Square wave (10%) | ~30 components |
| Sawtooth wave | ~30 components |

Discontinuous signals required significantly more harmonics due to Gibbs phenomenon.

---

## 🎓 Academic Context

This assignment was completed as part of ELI220 (Signals and Systems) at the University of Pretoria.

The work demonstrates:

- Analytical signal processing
- Fourier analysis
- Numerical implementation in Python
- Visualisation of convergence behaviour
