# Predictive Maintenance Analysis 

## Project Overview
This project analyzes industrial machine sensor data to understand operating conditions associated with machine failures. The analysis focuses on identifying high-risk patterns using statistical thresholds and exploratory data analysis, without applying machine learning models.

The goal is to build an explainable and analyst-friendly predictive maintenance workflow using sensor data.

---

## Tech Stack
- **Python** (Pandas, Seaborn, Matplotlib)
- **Jupyter Notebook**
- **Dataset**: AI4I 2020 Predictive Maintenance Dataset (Kaggle)

---

## Analysis Performed
- Analyzed machine failure distribution to understand class imbalance
- Compared sensor behavior between failed and healthy machines
- Visualized key failure indicators using correlation heatmaps
- Used boxplots to compare sensor distributions for failed vs. healthy machines
- Defined high-risk operating conditions using percentile-based thresholds

---

## Key Insights
- Failed machines consistently showed higher air temperature, torque, and tool wear
- Extreme sensor values (top 10%) were strongly associated with machine failures
- Rule-based risk flags successfully identified high-risk machines without using ML models

---

## Business Relevance
- Enables early identification of machines operating under risky conditions
- Helps maintenance teams prioritize inspections based on sensor thresholds
- Demonstrates explainable, data-driven decision support for predictive maintenance

---

## Files in This Repository
- `predictive_maintenance_analysis.ipynb` — Complete exploratory analysis notebook
- `images/` — Key visualizations from the analysis (heatmaps and boxplots)

---

## Notes
This project intentionally avoids machine learning to keep the analysis interpretable and easy to explain for operational decision-making.

