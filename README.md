# Seasonal Agriculture Performance Analysis

**VOIS AICTE Batch1 2026-2027 — Major Project**

## Problem Statement
Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability and market conditions. As a result, agricultural performance may differ from one season to another. This project analyzes seasonal farm data to identify meaningful patterns, trends, relationships and variations in yield, cost, profit, water usage and disease/pest risk across seasons.

## Dataset
`seasonal_agriculture_performance_dataset.csv` — 4,000 farm records across multiple Indian states, crops, and the three agricultural seasons (**Kharif, Rabi, Zaid**), including:
- Environmental conditions: rainfall, temperature, humidity, soil pH/moisture, sunlight
- Farming inputs: fertilizer, pesticide, irrigation method, seed quality, NPK levels
- Economic outcomes: yield, production, cost, revenue, profit, water usage/efficiency, disease/pest risk

## Analysis
`Seasonal_Agriculture_Performance_Analysis.ipynb` covers:
- Data cleaning (missing value imputation by season, duplicate checks)
- Season-wise performance comparison (yield, profit, water efficiency, disease/pest risk)
- Correlation analysis between environmental factors and outcomes
- Irrigation method effectiveness across seasons
- Crop-wise profitability by season
- Key findings and data-driven recommendations

## Key Findings
- Kharif has the highest average yield but also the highest variability and disease/pest risk
- Average profit margin is negative across all seasons, worsening from Kharif → Rabi → Zaid
- Drip irrigation shows a clear yield advantage in the drier Rabi and Zaid seasons
- No single environmental variable strongly predicts yield alone — performance is driven by a combination of factors

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Files
- `seasonal_agriculture_performance_dataset.csv` — raw dataset
- `Seasonal_Agriculture_Performance_Analysis.ipynb` — full analysis notebook
