# Stroke Prediction: EDA and Machine Learning

Assignment 3 (EDA) and Assignment 4 (ML Model Application & Evaluation).

## Dataset
- **Name:** Stroke Prediction Dataset
- **Source:** [Kaggle (fedesoriano)](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- **Size:** 5110 rows, 12 columns (5109 rows after cleaning)
- **Target:** `stroke` (1 = stroke, 0 = no stroke), about 4.9% positive (imbalanced)

## Problem
Predict whether a patient is likely to have a stroke from health and lifestyle information.
Problem type: **Classification**.

## What the notebook contains
1. **Data cleaning and preprocessing:** missing BMI (median imputation, train only), outlier clipping, encoding, scaling, log transform, feature engineering, stratified train/test split.
2. **Assignment 3, EDA:** univariate, target analysis, bivariate, correlation heatmap, multivariate, patterns/anomalies, final findings.
3. **Assignment 4, Modeling:** Logistic Regression, Decision Tree, Random Forest, KNN.

## Evaluation metrics
Accuracy, Precision, Recall, F1-Score, Confusion Matrix (also ROC-AUC).

## Results (test set)
| Model | Accuracy | Precision | Recall | F1 | ROC-AUC |
|---|---|---|---|---|---|
| Logistic Regression | ____ | ____ | ____ | ____ | ____ |
| Decision Tree | ____ | ____ | ____ | ____ | ____ |
| Random Forest | ____ | ____ | ____ | ____ | ____ |
| KNN | ____ | ____ | ____ | ____ | ____ |

**Best model:** ____ because ____ (Recall is the key metric, since missing a stroke case is costlier than a false alarm).

## Key EDA findings
- Dataset is highly imbalanced (~19:1).
- Age is the strongest factor; stroke rate rises sharply after 60.
- Hypertension, heart disease and high glucose are linked with higher stroke rate.
- BMI, gender and residence type are weak features.

## How to run
1. Open the notebook in Kaggle, Colab or Jupyter.
2. Add the dataset `healthcare-dataset-stroke-data.csv` (path in the first cell may need changing).
3. Run all cells top to bottom.

## Libraries
pandas, numpy, matplotlib, seaborn, scikit-learn
