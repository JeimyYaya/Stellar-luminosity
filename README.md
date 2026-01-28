# Stellar Luminosity Regression from First Principles

## Overview
This repository contains two Jupyter notebooks implementing linear and polynomial regression models **from scratch** to model stellar luminosity as a function of stellar mass and temperature.

The objective is to understand regression not as a black box, but as a fundamental computational and architectural capability, relevant for modern enterprise and cloud-based intelligent systems.

Only basic numerical tools are used:
- Python
- NumPy
- Matplotlib

No machine learning libraries are used.

---

## Repository Structure
```
├── README.md  
├── 01_part1_linreg_1feature.ipynb  
└── 02_part2_polyreg.ipynb  
```
---

## Datasets

### Part I (Single Feature)
- M: Stellar mass (solar masses)
- L: Stellar luminosity (solar luminosities)

### Part II (Multiple Features)
- M: Stellar mass
- T: Effective temperature (Kelvin)
- L: Stellar luminosity

All datasets are defined **directly inside the notebooks** as NumPy arrays.

---

## Learning Objectives
- Implement regression models from first principles
- Understand loss functions and gradients
- Compare vectorized and non-vectorized gradient descent
- Analyze convergence behavior
- Explore nonlinear and interaction effects
- Interpret model parameters in an astrophysical context
