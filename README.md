This repository contains a machine learning project for detecting fraudulent credit card transactions. Using a dataset of anonymized credit card transactions, the goal is to build and evaluate models that can effectively distinguish between legitimate and fraudulent activity.

**Dataset**
The dataset used is the Kaggle Credit Card Fraud Detection dataset, which contains transactions made by European cardholders in September 2013. It consists of 284,807 transactions, of which 492 are frauds (~0.172%).

Features are numerical, resulting from a PCA transformation for confidentiality.
The dataset is highly imbalanced, making it ideal for testing fraud detection techniques.

This repository includes a Jupyter Notebook that demonstrates:
- Exploratory Data Analysis (EDA)
- Handling data imbalance
- Feature scaling and preprocessing
- Model training and evaluation
- Metrics such as Precision, Recall, F1-Score, and ROC AUC
- Visualization of results

**Techniques Used**
- Logistic Regression
- Decision Trees
- Random Forest
- Confusion Matrix & Classification Reports

To run the notebook, make sure you have the following installed:

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
