# Machine Learning Lab 08: Trees, Forests & Costly Decisions

## Project Overview
This project explores machine learning classification using the Pima Indians Diabetes Dataset. It focuses on decision trees, random forests, model comparison, feature importance, and cost-sensitive decision-making.

## Objectives
- Explore and audit the dataset.
- Handle suspicious zero values as missing values.
- Train and evaluate machine learning models.
- Compare model performance using cross-validation.
- Examine feature importance.
- Analyze decision thresholds using different error costs.

## Dataset
**Dataset:** Pima Indians Diabetes Dataset

The dataset contains 768 records and 9 columns, including patient features and the target variable `Outcome`.

## Models Used
- Baseline Classifier
- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression

## Key Results
- Random Forest Cross-Validation ROC-AUC: 0.836 ± 0.018
- Logistic Regression Cross-Validation ROC-AUC: 0.837 ± 0.020
- Random Forest Test Accuracy: 0.755
- Selected threshold in the initial cost analysis: 0.225

## Tools & Libraries
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Repository Contents
- `Lab08_Trees_Forests_Costly_Decisions.ipynb` — Jupyter Notebook containing the implementation and results.

## Conclusion
This project demonstrates how different classification models can be evaluated and how decision thresholds can be adjusted according to the cost of false positives and false negatives.

**Note:** This is an educational machine learning experiment, not a medical diagnostic tool.
