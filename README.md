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

## AWS SageMaker Execution Evidence

### Upload and Execution Process

Both Jupyter notebooks were uploaded to AWS SageMaker using SageMaker Studio.
The notebooks were added to the SageMaker file system through the Studio
interface and opened directly in a managed Jupyter environment.

Once uploaded, all cells in both notebooks were executed sequentially to verify
that the code runs correctly in the cloud environment without errors.

---

### Execution Screenshots

The following screenshots provide evidence of successful execution in AWS
SageMaker:

- Both notebooks visible and opened in SageMaker Studio
<img width="1880" height="338" alt="image" src="https://github.com/user-attachments/assets/7f41ac6c-4b89-4c3c-95bc-160864cc247e" />

- All cells executed successfully with outputs displayed

## Part 1

<img width="1348" height="573" alt="image" src="https://github.com/user-attachments/assets/14b54a83-fece-4b6c-9f75-113c970e78a2" />

<img width="899" height="716" alt="image" src="https://github.com/user-attachments/assets/c4b17e98-8135-41b9-936a-04ae8be6ef3e" />

<img width="523" height="190" alt="image" src="https://github.com/user-attachments/assets/4eb96b7a-668e-42c4-bfe7-3a80b0adb680" />

<img width="705" height="632" alt="image" src="https://github.com/user-attachments/assets/5d964c73-caf5-48dc-817a-31c45741b627" />

<img width="627" height="293" alt="image" src="https://github.com/user-attachments/assets/25fe7b9a-67cb-4bf2-b961-3ec2a77cc02c" />

<img width="562" height="213" alt="image" src="https://github.com/user-attachments/assets/b388d842-6ab6-4bec-af53-a4b061359d78" />

<img width="605" height="327" alt="image" src="https://github.com/user-attachments/assets/e23bb81f-846a-463f-836e-29b7c77ed418" />

<img width="874" height="704" alt="image" src="https://github.com/user-attachments/assets/fb04d07f-f899-4a92-998f-6893e62dc370" />

<img width="784" height="323" alt="image" src="https://github.com/user-attachments/assets/40878e09-139a-4d94-81c4-ea51ed93471e" />

<img width="838" height="706" alt="image" src="https://github.com/user-attachments/assets/25aced6b-e2e3-40e0-9f88-be80cf836bf8" />

---
## Part 2
<img width="882" height="197" alt="image" src="https://github.com/user-attachments/assets/515ceac3-2f6d-4403-b8de-66b83e359b36" />

<img width="807" height="701" alt="image" src="https://github.com/user-attachments/assets/272c0122-66d0-4a09-94da-62a4934dc97c" />

<img width="766" height="207" alt="image" src="https://github.com/user-attachments/assets/28cf040a-ca20-495a-b305-ebc93a102951" />

<img width="576" height="373" alt="image" src="https://github.com/user-attachments/assets/e4a087c8-b9f0-47b5-82fb-2fefc54d27b7" />

<img width="651" height="339" alt="image" src="https://github.com/user-attachments/assets/779d49ba-f908-4503-9ab0-3de09c0b97f4" />

<img width="699" height="680" alt="image" src="https://github.com/user-attachments/assets/1e1d772b-0389-4d2a-b4b5-1a57f61ca470" />

<img width="909" height="709" alt="image" src="https://github.com/user-attachments/assets/bb4ab60e-4330-475b-9dbd-fed224a0835b" />

<img width="684" height="395" alt="image" src="https://github.com/user-attachments/assets/717a70b8-56ff-4797-82dd-d8aeb9b12adf" />

<img width="756" height="316" alt="image" src="https://github.com/user-attachments/assets/673afb68-83a9-43d6-842d-9be4dacb4260" />

---
- At least one plot rendered correctly within the SageMaker environment
<img width="723" height="569" alt="image" src="https://github.com/user-attachments/assets/9e692132-bdf6-4e8e-bf92-abc9f2128236" />


---

### Local vs SageMaker Execution Comparison

The behavior of the notebooks in AWS SageMaker was consistent with local
execution. All computations, training processes, and visualizations produced
the same results.

No significant differences were observed between local execution and SageMaker,
other than the cloud-based execution environment and resource management
provided by AWS.

