# Mapping Autonomic and Lifestyle Drivers of Glycemic Variability (N-of-1 ML Pipeline)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20567759.svg)](https://doi.org/10.5281/zenodo.20567759)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Official computational repository for the preprint:  **"Mapping Autonomic and Lifestyle Drivers of Glycemic Variability: An N-of-1 Machine Learning Approach Using Continuous Glucose Monitoring"**

## 📌 Abstract
Standard biomedical informatics relies heavily on population-scale cohorts, which frequently mask highly individualized phenotypic variations. This project implements an end-to-end machine learning and time-series informatics pipeline aggregating high-frequency continuous glucose monitoring (CGM) telemetry ($N = 3,296$) and consumer wearable biometrics (HRV, RHR, Sleep, PAI, Steps). We utilize XGBoost paired with SHapley Additive exPlanations (SHAP) to uncover non-linear autonomic and lifestyle drivers of metabolic volatility.

## 📁 Repository Contents
- `src/`: Core Python modules for computing advanced glycemic metrics (MAGE, Glucose CV) and temporal day-binning.
- `notebooks/`: Step-by-step Jupyter Notebooks covering pre-processing, feature correlation, model optimization, and SHAP interpretability analysis.
- `figures/`: High-resolution analytical plots and SHAP feature attribution distributions.

## 🚀 Quick Start

### Installation
```bash
git clone [https://github.com/chintalacheri/N-of-1-Glycemic-Variability-ML.git](https://github.com/chintalacheri/N-of-1-Glycemic-Variability-ML.git)
cd N-of-1-Glycemic-Variability-ML
pip install -r requirements.txt
