# Titanic Survival Analysis

## Project Structure

I tried to keep the project organized in a way that makes it easy to follow along and build on later. Here’s how I’ve structured things:

titanic_analysis/
│
├── data/                     # This is where the raw Kaggle dataset lives (train.csv, test.csv, gender_submission.csv).
│                             # I keep the original files untouched so I can always go back to them.
│
├── notebooks/                # Jupyter notebooks for different stages of the analysis.
│   ├── titanic_eda.ipynb   # First look at the dataset, summary stats, and visualizations.
│ 
│
├── scripts/                  

├── outputs/                  # Any generated plots, reports, or saved model predictions.
│
├── requirements.txt          # List of Python dependencies so the environment can be recreated easily.
├── README.md                 # Project documentation (this file).
└── .gitignore                # Keeps junk files (like venv, __pycache__, and notebook checkpoints) out of Git.
## Overview
Exploratory Data Analysis (EDA) of the Titanic dataset to identify factors that influenced passenger survival rates.

## Dataset Source
Kaggle Titanic: Machine Learning from Disaster (https://www.kaggle.com/c/titanic/data)

## Tools & Technologies
- Python 3.x
- Pandas & NumPy (Data Manipulation)
- Matplotlib & Seaborn (Visualization)
- Jupyter Notebook 

## Key Findings
1. **Overall Survival Rate**: 38.4% of passengers survived
2. **Gender Disparity**: 74.2% of females survived vs only 18.9% of males
3. **Class Impact**: 63% of 1st class survived vs only 24% of 3rd class
4. **Age Factor**: Children (0-12) had 59% survival rate vs 38% overall

## Visualizations Generated
- `overall_survival.png`: Overall survival distribution
- `survival_by_gender.png`: Gender-based survival analysis
- `survival_by_class.png`: Class-based survival analysis
- `age_distribution.png`: Age distribution of survivors
- `correlation_heatmap.png`: Feature correlation matrix

## How to Run
1. Clone repository: `git clone https://github.com/spacepriest8/titanic_analysis.git`
2. Install requirements: `pip install -r requirements.txt`
3. Open notebook: `jupyter notebook notebooks/titanic_eda.ipynb`