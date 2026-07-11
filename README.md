# Predictioneer: Epidemiological Spatiotemporal Forecasting

[![Project Status: 1st Place Winner](https://img.shields.io/badge/Competition-1st%20Place%20Winner-gold.svg)](#)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-%23145A32.svg?style=flat)](https://xgboost.readthedocs.io/)

[cite_start]An advanced epidemiological framework engineered by team *Atomic Algowizards* to track outbreak dynamics and forecast mortality counts and Case Fatality Ratios (CFR)[cite: 1131, 1139]. [cite_start]This production-grade architecture leverages geostatistical modeling and environmental constraints to map global transmission patterns[cite: 1149, 1150].

> 🏆 **Achievement:** Awarded **1st Place** out of all competing teams for data engineering precision and predictive accuracy.

---

## ⚡ Technical Highlights & Execution

* [cite_start]**Geostatistical Imputation Pipeline:** Handled severe spatial data gaps by benchmarking Inverse Distance Weighting (IDW using Haversine formulas), Ball Tree neighbors, and Gaussian Kriging models[cite: 1324, 1330, 1337, 1347].
* [cite_start]**Advanced Feature Engineering:** Extracted multi-scale spatial dependencies including radius-based **Spatial Lag** variables [cite: 1358][cite_start], **DBSCAN Regional Clustering** [cite: 1363][cite_start], and high-density proximity matrices using **cKDTree Spatial Density**[cite: 1370, 1371].
* [cite_start]**Biomedical Climatology Analytics:** Integrated global multi-year climate data to model the non-linear relationship between viral transmission efficiency and average surface temperatures[cite: 1350, 1352].
* [cite_start]**Ensemble Architecture:** Built and validated multiple ML/DL frameworks, deploying a high-performance **Bagging XGBoost** ensemble model for death prediction ($\text{RMSE}: 32.23$) and a optimized **Gradient Boosting Regressor** for CFR mapping ($\text{RMSE}: 0.570$)[cite: 1575, 1656, 1657]. [cite_start]Tested deep residual network baselines with skip connections for calibration[cite: 1533, 1534].

---

## 🛠️ Specialized Toolkits

* [cite_start]**Machine & Deep Learning:** `XGBoost`, `scikit-learn`, `PyTorch` (Residual Dense Blocks)
* [cite_start]**Geospatial & Proximity Engines:** `GeoPandas`, `cKDTree` / `BallTree` (Haversine Math)
* [cite_start]**Scientific Computing:** `Pandas`, `NumPy`, `SciPy`, `Matplotlib`, `Seaborn` 

---
[cite_start]*Developed by Varun Ram Narayanan, Raj Singh Yadav, & Shreshth Raj (IIT Bombay)*
