# Case Interview – Predicting Water Damage Frequency

This repository contains the end-to-end analysis and modeling work developed for a technical case interview.  
The task was to **predict the expected number of water-damage claims for the year 2025** based on historical policy and claims data (2020–2024).

---

## Overview

This project applies an **actuarial–data science approach** using Python and Generalized Linear Models (GLMs).  
It includes data exploration, feature engineering, model selection, validation, and portfolio-level predictions.

---

## Contents

### Main Files

- **`Case_Interview_Public.ipynb`**  
  Contains the complete workflow, including:
  - Data preparation and exploratory analysis  
  - Risk factor assessment *(Building Class, Dwelling Type, Area Band, Year)*  
  - GLM frequency modeling *(Poisson with log-link)*  
  - Interaction testing *(e.g., area × year)*  
  - Model validation and performance review  
  - 2025 portfolio prediction and uncertainty quantification  

### Directories

- **`data/`** – anonymized input data  
- **`instructions/`** – problem statement *(redacted for confidentiality)*  

---

## Key Results

- **Best model:** Poisson GLM with *area × year* interaction  
- **Target year:** 2025  
- **Predicted total claim cost:** 85.8 M SEK  
- **Premium required for 70% loss ratio:** 122.5 M SEK  
- **Uncertainty analysis:**  
  Confidence intervals derived from the GLM covariance matrix identify higher variability in small or underrepresented risk segments.

---

## Tools

- Python 3.11  
- pandas, numpy, statsmodels, matplotlib, seaborn  

---

## Notes

All data and materials have been anonymized.  
This project is provided **for demonstration and educational purposes only**.