# Global Stability Analysis of Laminar Flows: NACA 0012 & 2412 🌬️🔬

[![Domain](https://img.shields.io/badge/Domain-Fluid_Dynamics-blue.svg)]()
[![Simulation](https://img.shields.io/badge/Simulation-MATLAB-orange.svg)](https://www.mathworks.com/products/matlab.html)
[![Validation](https://img.shields.io/badge/Validation-ANSYS_Fluent-goldenrod.svg)](https://www.ansys.com/)
[![Universidad de Sevilla](https://img.shields.io/badge/Academic-Universidad_de_Sevilla-red?style=flat-square&logo=university&logoColor=white)](https://www.us.es/)

A comprehensive numerical study on the global stability of laminar flows around aerodynamic profiles, focusing on the NACA 0012 and NACA 2412 airfoils. 

This repository contains the documentation and presentation for the **Bachelor's Thesis (Trabajo Fin de Grado - TFG)** in Aerospace Engineering at Universidad de Sevilla (2022-2023).

---

## 🔒 Confidentiality Notice

**The source code used for the numerical simulations in this project is strictly confidential.** An NDA (Non-Disclosure Agreement) was signed with the thesis supervisor and the Department of Aerospace Engineering and Fluid Mechanics. Therefore, the custom solvers and scripts used to compute the base flows and extract the eigenvalues cannot be publicly shared in this repository.

---

## 📌 Project Overview

Understanding the stability of laminar flows is critical in aerodynamics to predict the transition to turbulence and vortex shedding phenomena. This thesis project was developed as a joint collaborative effort: one profile (NACA 0012) was analyzed by Alejandro Rivera, while the cambered profile (NACA 2412) was analyzed by Pablo Sánchez, culminating in a joint defense comparing both aerodynamic behaviors.

### 🎯 Key Objectives & Scope
* **Mathematical Formulation:** Definition of the governing Navier-Stokes equations and boundary conditions for 2D steady basic flows.
* **Linear Perturbation Analysis:** Introduction of linear perturbations to study the global stability of the flow.
* **Eigenvalue Extraction:** Numerical computation to identify stable and unstable modes within the flow field, determining the critical Reynolds numbers and angles of attack that trigger instabilities.
* **Solver Convergence:** Detailed analysis of mesh convergence and eigenvalue stabilization.
* **CFD Validation:** Direct comparison of the custom numerical results with commercial CFD software (ANSYS Fluent), analyzing the transient regime and vortex shedding frequencies.
* **Profile Comparison:** Evaluating how the camber of the NACA 2412 affects the stability boundaries compared to the symmetric NACA 0012.

## 📂 Repository Contents

Since the source code is restricted, this repository serves as a technical documentation archive:

* **`docs/`**: Contains the final Bachelor's Thesis report (`Report.pdf`) detailing the mathematical methods and results, along with the joint executive presentation (`Presentation.pdf`) used for the thesis defense.

## 👨‍💻 Authors

* **Alejandro Rivera Míguez**

---

Supervisor: **Prof. Miguel Ángel Herrada Gutiérrez**  
Department of Aerospace Engineering and Fluid Mechanics | Universidad de Sevilla

---
*Disclaimer: This is an academic Bachelor's Thesis. The documentation provided is intended for educational demonstration of advanced fluid mechanics concepts.*
