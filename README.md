# Diabetes ML Project

This project explores supervised machine learning techniques to predict the likelihood of diabetes from clinical measurements. The workflow combines exploratory data analysis in `project.ipynb`, a cleaned/tabular dataset (`diabetes.csv`), and documentation from the proposal PDF.

## Project Goals
- understand feature distributions and correlations related to diabetes onset
- compare baseline classifiers (logistic regression, tree-based ensembles, etc.)
- quantify performance with cross-validation and metrics such as ROC-AUC, precision/recall, and calibration curves
- highlight actionable insights that could help healthcare teams prioritize screenings

## Dataset
`diabetes.csv` contains anonymized patient-level attributes (e.g., glucose level, BMI, pregnancies, age). Missing values are handled directly in the notebook so the CSV remains the single source of raw inputs.

## Repository Contents
- `project.ipynb` – the main exploratory data analysis + model experimentation notebook
- `diabetes.csv` – source dataset used throughout the notebook
- `Project Proposal .pdf` – supporting document outlining the research motivation and plan
- `README.md` – this overview and usage guide

## Getting Started
1. Create a Python environment with Jupyter and common ML libraries (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`).
2. Launch Jupyter Lab/Notebook and open `project.ipynb`.
3. Run the cells sequentially to reproduce preprocessing, model training, and evaluation steps.

Feel free to extend the notebook with additional models, feature engineering, or reporting modules before deploying to production or wrapping the logic into a Python package.