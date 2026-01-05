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

## Installation
1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook`
