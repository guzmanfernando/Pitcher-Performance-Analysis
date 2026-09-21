# Pitcher-Performance-Analysis
# Analyzing Elite Pitcher Performance with Adjusted Metrics

An empirical analysis and predictive modeling project evaluating the performance and value (WAR) of five elite Major League Baseball pitchers over 15-year prime windows using era- and park-adjusted metrics.

## 📌 Project Overview
This study analyzes 75 individual seasons across five Hall of Fame-caliber pitchers: Roger Clemens, Pedro Martinez, Randy Johnson, Greg Maddux, and Clayton Kershaw. The primary goal is to evaluate how distinct pitching styles (power/velocity vs. finesse/control) translate into overall player value as measured by Wins Above Replacement (WAR).

## 📊 Key Findings & Model Performance
- **Run Prevention & Strikeouts:** ERA+ (run prevention adjusted for era/park) and total Strikeouts (SO) serve as the strongest predictors of pitcher WAR.
- **Model Accuracy:** The Multiple Linear Regression model successfully captures 71.7% of the variance in WAR across the dataset.

| Metric | Model Score |
| :--- | :--- |
| **R² Score** | 0.717 (71.7%) |
| **Mean Absolute Error (MAE)** | 1.15 Wins |
| **Root Mean Squared Error (RMSE)** | 1.47 Wins |

*(For full statistical distribution plots, correlation heatmaps, and actual vs. predicted WAR charts, refer to the Appendices in `reports/CSS_300_FinalProject_Guzman.pdf`)*

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Model:** Multiple Linear Regression

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/guzmanfernando/Pitcher-Performance-Analysis.git](https://github.com/guzmanfernando/Pitcher-Performance-Analysis.git)
   cd Pitcher-Performance-Analysis
