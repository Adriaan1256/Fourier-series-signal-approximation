# Fourier Series Signal Approximation

## 📌 Overview

This project explores the analytical derivation and numerical approximation of Fourier Series representations for various periodic signals.

The objective was to:

- Derive Fourier coefficients analytically
- Implement Fourier expansions in Python
- Visualise approximation accuracy
- Determine the number of harmonics required for accurate reconstruction

The following signals were analysed:

- Sine wave: x(t) = sin(2πt)
- Square wave (50% duty cycle)
- Square wave (10% duty cycle)
- Sawtooth wave: x(t) = t, 0 ≤ t ≤ 1

---

## 🎯 Objectives

- Derive Fourier series coefficients for each signal
- Implement numerical Fourier approximations in Python
- Compare approximation quality for different harmonic counts
- Determine minimum number of components required for accurate graphical representation

---

## 🛠 Tools & Technologies Used

- Python 3
- NumPy
- Matplotlib
- SciPy (signal module)
- Fourier Series Theory (Continuous-time signal analysis)

---

## 🏗 Project Structure

Each signal is implemented in a separate module:

- `q1_sine_wave.py`
- `q2_square_wave_50.py`
- `q3_square_wave_10.py`
- `q4_sawtooth_wave.py`

Each script:
- Computes Fourier coefficients
- Reconstructs the signal using increasing harmonics
- Plots the original and approximated signals

---

## 📊 Key Findings

| Signal Type | Harmonics Required for Good Approximation |
|------------|-------------------------------------------|
| Sine wave | 1 component |
| Square wave (50%) | ~40 components |
| Square wave (10%) | ~30 components |
| Sawtooth wave | ~30 components |

The results demonstrate how discontinuities significantly increase harmonic requirements due to the Gibbs phenomenon.

---

## 🚀 How to Run

### 1. Install dependencies
