# Diabetes Prediction Using Machine Learning

This project predicts whether a person is diabetic based on medical diagnostic measurements from the Pima Indians Diabetes dataset.

## Overview

The notebook follows a complete binary classification pipeline:

1. Load and inspect the dataset.
2. Separate features and target (`Outcome`).
3. Standardize features using `StandardScaler`.
4. Split into train/test sets with stratification.
5. Train an SVM classifier (`SVC` with linear kernel).
6. Evaluate using accuracy and run sample predictions.

## Tech Stack

- Python 3.9+
- NumPy
- Pandas
- scikit-learn
- Jupyter Notebook

## Project Structure

- `Diabetes prediction using ML.ipynb` - Main notebook for EDA, training, evaluation, and inference
- `diabetes.csv` - Input dataset
- `requirements.txt` - Primary Python dependencies
- `requirement.txt` - Compatibility alias (references `requirements.txt`)
- `.gitignore` - Standard Python/Jupyter ignore rules
- `LICENSE` - MIT License

## Results

Model performance from the current notebook run:

| Metric | Value |
|--------|-------|
| Training Accuracy | 77.27% |
| Test Accuracy | 77.27% |

## Screenshots / Output Snapshot

You can add notebook output screenshots in an `assets/` folder and reference them here for stronger project presentation on GitHub.

Example markdown once screenshot is added:

```md
![Model Output](assets/model-output.png)
```

## Setup and Run

### 1. Clone the repository

```bash
git clone https://github.com/HARSH-7858/Diabetes-prediction-using-ML.git
cd Diabetes-prediction-using-ML
```

### 2. Create and activate a virtual environment

Windows (PowerShell):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

macOS/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch notebook

```bash
jupyter notebook
```

Open `Diabetes prediction using ML.ipynb` and run all cells in order.

## Model Configuration

- Algorithm: Support Vector Classifier (`SVC`)
- Kernel: `linear`
- Test size: `0.2`
- Stratification: `Outcome`
- Random state: `2`
- Feature scaling: `StandardScaler`

## Future Enhancements

- Add model persistence with `joblib`.
- Track additional metrics: precision, recall, F1-score, ROC-AUC.
- Add cross-validation.
- Refactor notebook logic into a reusable Python script or API.

## Author

Harsh Raj Shrivastav
