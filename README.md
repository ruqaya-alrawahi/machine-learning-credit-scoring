# Australian Credit Approval Classification

Machine learning classification project developed for the Machine Learning for Engineers course.

## Project Overview
This project develops an automated machine learning system for predicting credit approval decisions using the Australian Credit Approval dataset from the UCI Machine Learning Repository.

The goal is to improve decision consistency, reduce processing time, and minimize financial risk compared to traditional manual approval systems.

## Dataset
- Source: UCI Machine Learning Repository
- Samples: 690
- Features: 14
- Classes: Approved / Denied

## Data Preprocessing
The preprocessing pipeline includes:

- Missing value imputation
- Label encoding
- Feature scaling using StandardScaler
- Stratified train-test split

## Machine Learning Models
The following models were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Support Vector Machine
- AdaBoost
- Gradient Boosting
- Multi-Layer Perceptron
- PCA + Random Forest
- K-Means Clustering

## Results

### Best Model: Gradient Boosting

| Metric | Score |
|--------|-------|
| Accuracy | 88.4% |
| Precision | 87.9% |
| Recall | 87.3% |
| F1 Score | 87.6% |

## Key Findings
- Ensemble methods achieved the best performance.
- Non-linear models outperformed linear models.
- Feature importance analysis highlighted credit score, employment status, debt level, and income as critical predictors.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Installation

```bash
git clone <your-repo-link>
cd australian-credit-approval-classification
pip install -r requirements.txt
