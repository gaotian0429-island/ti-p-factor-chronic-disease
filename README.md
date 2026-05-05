# ti-p-factor-chronic-disease
Analysis scripts for the manuscript: "From Psychological Distress to Multi-System Morbidity: A Transdiagnostic Internalizing Factor Predicts Chronic Disease Onset".
# From Psychological Distress to Multi-System Morbidity

**Official code repository for the manuscript:** 
*"From Psychological Distress to Multi-System Morbidity: A Transdiagnostic Internalizing Factor Predicts Chronic Disease Onset"*

## Overview

This repository contains the custom analysis scripts (Python and Mplus) used in our study to investigate the impact of the transdiagnostic internalizing (TI) p-factor on chronic disease onset. The code covers the extraction of the latent factor, survival analysis (Cox regression), generalized linear models (GLM) for biomarkers, and mediation analysis.

## Repository Structure

The core analysis codes are organized as follows:

*   **`Bi-ESEM.inp`**
    *   Mplus input script for the Bifactor Exploratory Structural Equation Modeling (Bi-ESEM). 
    *   *Purpose:* Used to extract the latent transdiagnostic internalizing (TI) p-factor from psychological distress items.
*   **`factor_disease_cox.ipynb`**
    *   Jupyter Notebook containing Python code for survival analysis.
    *   *Purpose:* Used to predict the risk of incident chronic diseases based on the TI factor (using Cox proportional hazards models).
*   **`factor_biomarker_glm.ipynb`**
    *   Jupyter Notebook containing Python code for Generalized Linear Models (GLM).
    *   *Purpose:* Used to calculate and evaluate the associations between the TI factor and various physiological biomarkers.
*   **`mediation_system.ipynb`**
    *   Jupyter Notebook containing Python code for mediation analysis.
    *   *Purpose:* Used to explore the underlying systemic pathways linking the TI factor to chronic disease onset.

## Contact
For any questions regarding the code or analysis, please contact the corresponding author as listed in the manuscript.
