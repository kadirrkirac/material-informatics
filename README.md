# Perovskite Stability Predictor: A Machine Learning Approach 🧪

This project focuses on predicting the thermodynamic and geometric stability of **ABO3-type perovskite structures**, specifically designed for research in **Solid Oxide Fuel Cells (SOFC)** composite cathodes. It was developed as part of a **TÜBİTAK** research project involving the production and characterization of **SCaSC-SDC** based composite cathodes.

## 🚀 Overview

Predicting the stability of new material compositions is a critical challenge in materials science. This tool combines **Machine Learning (ML)** with classical **Solid-State Physics** to provide a dual-layer validation for material stability.

Specifically, it targets the **SCaSC** ($Sr_{0.7}Ca_{0.2}Sm_{0.1}CoO_3$) system to ensure these complex compositions maintain a stable perovskite phase during high-temperature synthesis.

## 🧠 Features

- **Automated Data Pipeline:** Fetches the latest crystallographic and thermodynamic data from the **Materials Project API**.
- **Hybrid Prediction Logic:** 
  - **Random Forest Regressor:** Trained on physical and chemical descriptors (electronegativity, atomic radii, valence electrons) via the **Magpie** preset.
  - **Goldschmidt Tolerance Factor ($t$):** Calculates geometric constraints to ensure the A and B site ions fit within the oxygen octahedra.
- **Robust Error Handling:** Includes safety checks for "unphysical" compositions (e.g., noble gases) or missing atomic data.

## 📊 Methodology

The model evaluates stability based on İonic radius and Formation Energy:
1.  **Formation Energy ($E_f$):** Predicted via ML. Lower (more negative) energy indicates higher thermodynamic stability.
2.  **Tolerance Factor ($t$):**
    $$t = \frac{r_A + r_O}{\sqrt{2}(r_B + r_O)}$$
    Where $r_A$ and $r_B$ are ionic radii, and $r_O$ is the radius of Oxygen.

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/perovskite-stability-ml.git](https://github.com/yourusername/perovskite-stability-ml.git)
