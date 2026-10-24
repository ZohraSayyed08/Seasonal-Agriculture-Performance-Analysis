# Seasonal Agriculture Performance Analysis

Individual final project for the AICTE and VOIS for Tech University Engagement Program virtual internship on Data Analytics (Vodafone Idea Foundation, implemented by Edunet Foundation).

## Problem
Agricultural performance differs from one season to another, but raw data does not show how. This project investigates seasonal differences in yield, profit and disease/pest risk. The problem statement and dataset were provided by the internship program.

## Dataset
`seasonal_agriculture_performance_dataset.csv`: 4,000 farm records across the Kharif, Rabi and Zaid seasons in India (provided by the program).

## Approach
Cleaned and explored the data using univariate, bivariate and multivariate analysis in Python (pandas, NumPy, matplotlib, seaborn), in Jupyter or Google Colab.

## Key findings
- Kharif had the highest average yield (5.63 t/ha), followed by Rabi (5.04) and Zaid (4.64)
- Kharif was the most profitable season (average Rs 1.79 lakh per farm). Zaid ran an average loss of Rs 24,805 per farm, with 64.5% of Zaid farms unprofitable
- Rainfall correlated strongly with disease/pest risk (r = 0.62) and almost not at all with yield (r = 0.03)
- Drip irrigation performed best in Kharif and Rabi, while sprinkler irrigation outperformed it in Zaid
- Disease/pest risk was highest in Kharif (54.5%) and lowest in Zaid (38.2%)

These are associations in this dataset, not proven causes.

## Future scope
Multi-year data, a yield and profit prediction model, region-level dashboards, real-time weather and price feeds.

## Files
- `Seasonal_Agriculture_Performance_Analysis.ipynb`: my analysis
- `seasonal_agriculture_performance_dataset.csv`: the dataset provided by the program
- `Seasonal_Agriculture_Performance_Analysis_PPT.pptx`: my project deck
- `Major Project_Seasonal Agriculture Performance Analysis..pdf`: the problem statement document provided by the program

## How to run
Open the notebook in Jupyter or Google Colab with the CSV in the same folder, and run all cells.

## Author
Zohra Sayyed
