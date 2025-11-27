# Second-Life Battery Analysis - Internship Assessment

**Author:** Aastik Wagadre

## Project Overview
This repository contains the solution for the LOHUM Summer Internship problem statement. The project analyzes battery feedstock from three OEMs to identify unknown electrical features, compare degradation patterns, and estimate State of Health (SOH).

## Contents
* **Analysis Notebook:** Python code for EDA and Machine Learning.
* **Report:** Formal PDF report detailing findings and methodology.
* **Model:** Serialized Random Forest model (`.pkl`) for SOH estimation.

## Key Findings
* **Feature 10:** Identified as **Discharge Capacity (Ah)** (Correlation: 1.0).
* **Best OEM:** OEM 3 demonstrated the highest consistency and predictability.
* **Model Performance:** Achieved an RMSE of **0.21** using Random Forest Regression.
