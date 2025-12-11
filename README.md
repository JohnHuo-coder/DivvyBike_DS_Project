# 🚲 Divvy Bike Usage Pattern Analysis — Chicago Land-Use Study

(A data analysis project exploring bike usage patterns across land-use types)

## 📌 Overview

This project analyzes Divvy bike usage patterns in Chicago across seven land-use types, using trip data from August–October 2025.
The goal is to understand how usage differs between weekdays and weekends, and how land-use context affects bike demand, supply imbalance, and operational risks.

Key indicators examined include:

- Mean hourly total trips

- Mean hourly net flow

- Usage frequency

- Bike type preference (classic vs. electric)

- Extreme net flow per dock

Insights from this analysis can inform operational planning, bike rebalancing strategies, and policy development.

## 📂 Repository Contents

| File | Description |
|------|-------------|
| **project_report_jingyu_huo.html** | Full project report with methodology, visualizations, conclusions, and recommendations |
| **project_code_jingyu_huo.ipynb** | Jupyter Notebook for data cleaning, feature engineering, EDA, and plotting |
| **requirements.txt** | Required Python packages for running the analysis |


## 🧰 Requirements

To reproduce the analysis, install dependencies with:

`pip install -r requirements.txt`

Ensure all required datasets are downloaded and are placed in the same folder as the notebook. (see Data Source section in the report to download data).

## 📊 Summary of Findings

- Strong weekday commuting patterns in Downtown & Planned Development areas

- Weekend usage shifts toward midday in most land-use types

- Electric bikes dominate weekday commuting; classic bikes gain share on weekends

- Planned Development stations show the most severe operational stress (multiple hours with extreme per-dock net flow > 0.5)

## 📝 Future Work

To derive more robust and generalizable patterns, future analysis should include multiple years of Divvy trip data, enabling seasonal comparisons and year-over-year trend evaluation.
