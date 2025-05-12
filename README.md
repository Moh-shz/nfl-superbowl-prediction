# NFL Super Bowl Winner Prediction

This repository contains the full data and code for the MSc Data Science dissertation project:  
**Forecasting Super Bowl Champions Using XGBoost: A Scenario-Based Analysis of Historical Window Impact and Feature Importance**

## Project Overview

The project develops a scenario-driven machine learning framework to forecast NFL Super Bowl champions, using XGBoost and team-level statistics (2002–2024).  
The study explores:
- The effect of historical data window size
- Forecasting at different NFL season stages
- Feature importance using gain-based and SHAP-based methods

Three practical forecasting scenarios were designed:
1. **Scenario 1: Pre-Super Bowl** (between the two finalists)
2. **Scenario 2: Pre-Playoffs** (all playoff teams)
3. **Scenario 3: Pre-Season** (all 32 teams)

A Case study on 2024 season and forward-looking prediction for the 2025 season are also included.

## Repository Structure

```
nfl-superbowl-prediction/
│
├── data/
│   ├── raw_data/ → Raw dataset
│   ├── prepared_data/ → Prepared dataset and dictionaries
│   ├── models_used_in_case_study_2024/ → Pre-trained models for 2024 case study
│   └── predictions_used_in_case_study_2024/ → Models predictions for the 2024 case study
│
└── notebooks/ → Jupyter notebooks for all experiments
```

## Data

The raw dataset is sourced from Kaggle:  
[NFL Team Stats 2002-2019 (ESPN Data)](https://www.kaggle.com/datasets/cviaxmiwnptr/nfl-team-stats-20022019-espn)
License: Creative Commons CC0 (Public Domain Dedication)

No personal or sensitive information is included.  
The data is used strictly for academic and research purposes.

## Official Release

The final version of the full code and data accompanying this MSc dissertation is archived at:  
[https://github.com/Moh-shz/nfl-superbowl-prediction/releases/tag/v1.0.0](https://github.com/Moh-shz/nfl-superbowl-prediction/releases/tag/v1.0.0)
