# Breast Cancer Prediction using Logistic Regression

## Project Overview

This project predicts whether a breast tumor is **Malignant (M)** or **Benign (B)** using the Breast Cancer Wisconsin (Diagnostic) dataset. A Logistic Regression model is trained on various tumor characteristics to classify the diagnosis.

## Dataset

The dataset contains measurements computed from digitized images of breast mass cell nuclei.

**Target Variable:**

* `diagnosis`

  * `M` = Malignant
  * `B` = Benign

**Features include:**

* radius_mean
* texture_mean
* perimeter_mean
* area_mean
* smoothness_mean
* compactness_mean
* concavity_mean
* concave points_mean
* symmetry_mean
* fractal_dimension_mean
* and their corresponding standard error (`_se`) and worst (`_worst`) values.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

1. Load the dataset
2. Data preprocessing and cleaning
3. Exploratory Data Analysis (EDA)
4. Feature selection
5. Train-test split
6. Train a Logistic Regression model
7. Evaluate the model using accuracy and confusion matrix
8. Make predictions

## Model Used

* Logistic Regression

## Model Performance

* Accuracy: **98.24%** 

## Installation

```bash
git clone https://github.com/koustav-nandi2005/Breast-Cancer-ML-.git

cd Breast-Cancer-ML-

pip install -r requirements.txt
```

## Run

If using a Jupyter Notebook:

```bash
jupyter notebook
```

Or, if you have a Python script:

```bash
python train.py
```

## Author

Koustav Nandi
