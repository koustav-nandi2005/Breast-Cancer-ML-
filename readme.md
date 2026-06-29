# Breast Cancer Prediction

## Project Overview

This project predicts whether a breast tumor is **Malignant (M)** or **Benign (B)** using machine learning.

## Dataset

Dataset: Breast Cancer Wisconsin (Diagnostic)

Target Variable:
- diagnosis
  - M = Malignant
  - B = Benign

Features include:
- radius_mean
- texture_mean
- perimeter_mean
- area_mean
- smoothness_mean
- compactness_mean
- concavity_mean
- symmetry_mean
- fractal_dimension_mean
- and other derived measurements.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Workflow

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Prediction

## Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine

## Accuracy

Example:

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 96% |
| Random Forest | 98% |

## Installation

```bash
git clone https://github.com/yourusername/Breast-Cancer-Prediction.git

cd Breast-Cancer-Prediction

pip install -r requirements.txt
```

## Run

```bash
python train.py
```

or

```bash
streamlit run app.py
```

## Author

Your Name