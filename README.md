# British Airways Data Science Job Simulation: Predictive & Operational Modeling

## Disclaimer
All datasets used in this project were provided as part of the **British Airways Data Science Job Simulation on Forage**. The data is not publicly available and is therefore not included in this repository.

## Overview
This repository contains my completed work for the **British Airways Data Science Job Simulation on Forage (January 2026)**. The simulation focuses on how data science supports British Airways’ operational planning and customer decision-making. Due to data usage and copyright restrictions, the original CSV datasets provided through Forage are **not included**. This repository contains the notebook workflows and analytical approaches used to complete each task.

## Project Structure
- `BATask1_MNC.ipynb` and `Lounge Eligibility Lookup - Task 1 BA_MNC.xlsx`: Operational modeling to estimate lounge demand at Heathrow Terminal 3.

- `BATask2_MNC.ipynb` and `BA_Task2PowerPoint_MNC.pptx`: Predictive modeling to identify factors influencing customer booking behavior.

## Task 1: Modeling Lounge Eligibility (Heathrow Terminal 3)
The objective of Task 1 was to create a **lookup table** that British Airways can use to estimate lounge eligibility percentages across different flight groupings. This approach allows the business to:
- Anticipate lounge demand
- Plan staffing and capacity
- Operate effectively without requiring exact flight or aircraft details

The task involved grouping flights, making assumptions about passenger eligibility, and designing a scalable method that could adapt to future schedule changes.

## Task 2: Predicting Customer Buying Behavior
The objective of Task 2 was to manipulate and prepare customer booking data to build a **high-quality predictive model** capable of identifying customers likely to complete a booking. This included:
- Exploratory data analysis and feature engineering
- Encoding categorical variables and handling class imbalance
- Training and comparing multiple machine learning models
- Evaluating performance using ROC-AUC, Recall, F1-score, Precision, and Accuracy
- Interpreting feature importance to understand key drivers of booking behavior
- Translating model results into actionable business insights

## Packages Used
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn
