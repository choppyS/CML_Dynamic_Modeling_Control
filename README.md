# Dynamical Modeling and Control of Chronic Myeloid Leukemia (CML)

This project explores the mathematical modeling, stability analysis, and control of Chronic Myeloid Leukemia (CML) progression, focusing on the competition between normal and leukemic cell populations and the development of mutations.

## 🔬 Project Overview
The study investigates a 3-compartment nonlinear dynamical system that represents the interactions between:
* **Normal Cells ($T_n$):** Healthy hematopoietic cells.
* **Sensitive Cancer Cells ($C_s$):** Leukemic cells responsive to treatment.
* **Resistant Cancer Cells ($C_r$):** Mutated leukemic cells resistant to standard therapies.

The goal is to design an optimal treatment strategy (control law) to drive the system from a "disease" equilibrium to a "healthy" state.

## 🛠 Technical Features
* **Stability Analysis:** Identification of equilibrium points and local/global stability using Jacobian linearization and Lyapunov methods.
* **Bifurcation Analysis:** Study of system behavior changes relative to the cancer growth rate ($\xi_n$).
* **Advanced Control Design:**
    * **Nonlinear Control:** Input-Output Feedback Linearization (FBL).
    * **Linear Control:** Linear Quadratic Regulator (LQR) applied to the linearized system.
* **Robustness Testing:** Evaluation of controller performance under parametric uncertainties and external disturbances.

## 💻 Software & Tools
* **MATLAB / Simulink:** Used for the entire simulation environment and controller implementation.
* **Pplane8:** Employed for phase portrait analysis and vector field visualization.

## 📄 Repository Contents
* `NLDC_Project.pdf`: The complete technical report containing mathematical derivations, stability proofs, and detailed results.
* `Presentation.pdf`: A summary presentation of the modeling approach and a comparison between FBL and LQR performance.

---
*Developed as part of the Master's Degree in Automation Engineering at the University of Naples Federico II.*
