# NFL Draft Model

## Overview
This project predicts NFL draft success from college statistics using machine learning. We analyze which college performance metrics best predict NFL outcomes, build a model to evaluate draft prospects, and identify historically overdrafted and underdrafted players.

## Key Questions
- Which college statistics most reliably predict NFL success?
- Which positions are most predictable from college data?
- Which draft classes were strongest and weakest?
- Which players were most overdrafted and underdrafted historically?

## Repo Structure
nfl-draft-model/
├── data/
│   ├── raw/              # Raw data files (not tracked)
│   └── processed/        # Cleaned dataset (not tracked)
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_college_stats.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_modeling.ipynb
│   ├── 05_evaluation.ipynb
│   └── 06_draft_class_analysis.ipynb
├── outputs/
│   └── figures/
├── src/
├── requirements.txt
└── README.md

## How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run notebooks in order: `01 → 06`
4. Data downloads automatically in notebook 01

## Data Source
Draft and college data pulled via [nfl_data_py](https://github.com/nflverse/nfl_data_py) — credit to the nflverse contributors.