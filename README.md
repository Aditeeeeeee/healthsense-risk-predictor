# HealthSense — Health & Lifestyle Risk Predictor

A machine learning project that predicts a person's health risk level (Low / Medium / High) based on lifestyle inputs like sleep, stress, activity and BMI. Built as a collaborative team project for our Master's application portfolio.

## Results
- Logistic Regression Accuracy: 98.67%
- Decision Tree Accuracy: 96.00%
- Cross Validation Average: 95.66% (LR) / 97.66% (DT)

## Features
- Predicts health risk level — Low, Medium or High
- Calculates a lifestyle score out of 100
- Gives personalised health tips based on inputs
- Compares two ML models with full evaluation

## Project Structure
```
healthsense-risk-predictor/
├── notebook_01_eda.ipynb          ← data exploration & charts
├── notebook_02_preprocess.ipynb   ← data cleaning & encoding
├── notebook_03_models.ipynb       ← model training & evaluation
├── notebook_04_predict.ipynb      ← prediction & health tips
├── data/                          ← dataset folder
├── visuals/                       ← all charts and graphs
└── README.md
```

## Dataset
Sleep Health and Lifestyle Dataset — Kaggle
400 records, 13 features including sleep duration, stress level, BMI, physical activity and more.

## Models Used
- Logistic Regression
- Decision Tree Classifier
- 5-Fold Cross Validation

## Key Findings
- Sleep Duration is the most important predictor (importance score: 0.685)
- Higher stress strongly correlates with less sleep (correlation: -0.8)
- Both models achieve above 96% accuracy

## How to Run
1. Clone this repository
2. Install requirements: `pip install pandas numpy scikit-learn matplotlib seaborn ipywidgets`
3. Download the dataset from Kaggle and place in `data/` folder
4. Run notebooks in order: 01 → 02 → 03 → 04

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

## Authors

Member 1
- Name: Aditi Jitendra Kumar
- Degree: BCA (Science)

Member 2
- Name: Sai Vikas Bhor
- Degree: BCA (Science)

## Project Context
This project was developed as a team of two as part of our Master's application portfolio.
Target program: MSc Data Analytics — University of Hildesheim
