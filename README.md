# Predictive Maintenance Analysis

## Project Overview
This project analyzes machine sensor data to identify operating conditions associated with equipment failure. Using exploratory data analysis and statistical techniques, the project focuses on understanding failure patterns and detecting high-risk machine behavior based on sensor readings.

---

## Tech Stack
- **Python** (Pandas, Seaborn, Matplotlib)
- **Jupyter Notebook**
- **Data Source**: AI4I 2020 Predictive Maintenance Dataset (<a href="https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset">UCI</a>)

---

## Key Analysis & Insights
- Examined machine failure distribution to understand imbalance between failed and healthy machines
- Compared sensor behavior (temperature, torque, tool wear) for failed vs. non-failed machines
- Used correlation analysis to identify relationships between sensor variables and machine failure
- Visualized failure indicators using heatmaps and boxplots for pattern detection

---

## Risk Analysis
- Defined high-risk operating conditions using percentile-based thresholds on sensor values
- Identified machines operating under extreme temperature, torque, or tool wear conditions
- Compared high-risk flags with actual machine failure outcomes to validate risk patterns

---

## Business Insights
- Machines operating under extreme sensor conditions showed higher failure occurrence
- Sensor-based thresholds can support early warning mechanisms for maintenance teams
- Analysis provides a data-driven foundation for prioritizing machine inspections

---

## Outcome
This project demonstrates how exploratory analysis of sensor data can support predictive maintenance strategies by identifying failure-prone operating conditions and enabling proactive decision-making.



