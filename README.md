# ⚾ Pitcher Performance Analysis: Evaluating Elite Pitchers with Adjusted Metrics

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

An empirical analysis and predictive modeling project evaluating the performance and value (WAR) of five elite Major League Baseball pitchers over 15-year prime windows using era- and park-adjusted metrics.

---

## 📌 Project Overview
This study analyzes 75 individual seasons across five Hall of Fame-caliber pitchers: Roger Clemens, Pedro Martinez, Randy Johnson, Greg Maddux, and Clayton Kershaw. The primary goal is to evaluate how distinct pitching styles (power/velocity vs. finesse/control) translate into overall player value as measured by Wins Above Replacement (WAR).

---

## 📊 Key Findings & Model Performance
- **Run Prevention & Strikeouts:** ERA+ (run prevention adjusted for era/park) and total Strikeouts (SO) serve as the strongest predictors of pitcher WAR.
- **Model Accuracy:** The Multiple Linear Regression model successfully captures 71.7% of the variance in WAR across the dataset.

| Metric | Model Score |
| :--- | :--- |
| **R² Score** | 0.717 (71.7%) |
| **Mean Absolute Error (MAE)** | 1.15 Wins |
| **Root Mean Squared Error (RMSE)** | 1.47 Wins |

*(For full statistical distribution plots, correlation heatmaps, and actual vs. predicted WAR charts, refer to the Appendices in `reports/CSS_300_FinalProject_Guzman.pdf`)*

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Model:** Multiple Linear Regression
