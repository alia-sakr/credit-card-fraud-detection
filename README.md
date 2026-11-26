# Credit Card Fraud Detection

Detects fraudulent card transactions in a heavily imbalanced dataset with a leakage-safe workflow: single-model baselines, then bagging, boosting and stacking ensembles, with SMOTE for class imbalance and a decision threshold chosen on the validation set.

**Tools:** Python, pandas, scikit-learn, imbalanced-learn

## Results (test set)
Best model: Gradient Boosting (HistGradientBoosting) – Average Precision 0.827, ROC-AUC 0.965, precision 0.948, recall 0.768. It caught 73 of 95 frauds with 4 false alarms among 56,651 legitimate transactions.

## Data
Kaggle – [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Put `creditcard.csv` next to the notebook to rerun it. The file is 150 MB, so it isn't included here.
