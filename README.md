# Diabetes Prediction using Machine Learning

A machine learning project that predicts whether a person is diabetic based on medical diagnostic measurements from the Pima Indians Diabetes dataset.

## Project Summary

This project uses a supervised classification workflow in a Jupyter Notebook:

1. Loads and explores the dataset from diabetes.csv.
2. Splits features and target variable (Outcome).
3. Standardizes feature values using StandardScaler.
4. Trains a Support Vector Machine classifier with a linear kernel.
5. Evaluates model performance using accuracy on train and test data.
6. Performs inference on custom input samples.

## Tech Stack

- Python 3.9+
- NumPy
- Pandas
- scikit-learn
- Jupyter Notebook

## Repository Structure

- Diabetes prediction using ML.ipynb: Main notebook containing data analysis, training, evaluation, and prediction.
- diabetes.csv: Dataset used for model training and testing.
- requirements.txt: Standard dependency file for Python environments.
- requirement.txt: Alias dependency file included for compatibility.

## Getting Started

### 1. Clone the repository

Use your repository URL after pushing to GitHub.

### 2. Create and activate a virtual environment

Windows (PowerShell):
python -m venv .venv
.\.venv\Scripts\Activate.ps1

macOS/Linux:
python3 -m venv .venv
source .venv/bin/activate

### 3. Install dependencies

pip install -r requirements.txt

### 4. Run the notebook

jupyter notebook

Then open Diabetes prediction using ML.ipynb and run all cells in order.

## Model Details

- Algorithm: Support Vector Classifier (SVC)
- Kernel: linear
- Test split: 20 percent
- Data split strategy: stratified by target class
- Random state: 2
- Feature scaling: StandardScaler

## Notes

- Ensure diabetes.csv is in the same directory as the notebook.
- For reproducibility, keep package versions pinned or constrained in requirements files.

## Future Improvements

- Add model persistence (joblib or pickle).
- Add cross-validation and additional evaluation metrics (precision, recall, F1, ROC-AUC).
- Package prediction logic into a reusable Python script or API.

## Author

Harsh Raj Shrivastav
