## Overview
This repository contains two Jupyter notebooks that demonstrate the use of Random Forest and other ensemble learning methods to tackle classification problems using company data and fraud check data. The notebooks include extensive use of Random Forest, along with Bagging, Boosting, and Stacking ensemble methods to compare performance across different setups.

The notebooks in this repository apply several ensemble techniques to:
- Predict sales categories ('high' vs 'low') based on various company metrics such as Sales, CompPrice, Income, etc.
- Classify individuals based on taxable income as either 'Risky' or 'Good' in a fraud detection scenario.
  
## Techniques Used
- Random Forest: An ensemble classifier that uses multiple decision trees to improve classification accuracy.
- Bagging: Helps reduce variance and overfitting in decision trees.
- Boosting: Focuses on converting weak learners into strong ones.
- Stacking: Combines the predictions of multiple classification models.
  
## Notebooks
- Random Forest on Company Data.ipynb: This notebook deals with predicting the 'Sales' category using various company-related metrics.
- Random Forest for Fraud Check.ipynb: This notebook uses Random Forest to classify individuals for fraud detection based on their taxable income.
