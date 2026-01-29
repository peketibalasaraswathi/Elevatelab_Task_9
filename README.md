# Elevatelab_Task_9

# Credit Card Fraud Detection using Random Forest

# Task Overview
This project focuses on detecting fraudulent credit card transactions using **Machine Learning**, specifically the **Random Forest** algorithm.  
The task demonstrates how to handle **imbalanced datasets**, evaluate models correctly, and apply **ensemble learning** techniques.

# Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

#  Dataset
- Credit Card Fraud Dataset (Synthetic / Kaggle Alternative)
- The dataset is highly imbalanced, with very few fraud cases compared to non-fraud cases.

#  Steps Performed
1. Loaded the dataset and analyzed class imbalance
2. Separated features and target variable
3. Performed stratified train-test split
4. Built a baseline Logistic Regression model
5. Implemented Random Forest classifier
6. Evaluated models using Precision, Recall, and F1-score
7. Visualized feature importance
8. Compared Random Forest with baseline model
9. Saved the trained model using Joblib

#  Model Evaluation
Accuracy is not used as the primary metric due to data imbalance.  
Instead, the following metrics are used:
- Precision
- Recall
- F1-score

#  Feature Importance
Random Forest provides feature importance scores, helping identify the most influential features in fraud detection.

# Saved Model
The trained Random Forest model is saved as:
```
random_forest_fraud_model.pkl
```
# Output
<img width="997" height="397" alt="Image" src="https://github.com/user-attachments/assets/e2c1e70b-1d48-4740-ae4e-ef2ca357404e" />
<img width="1321" height="673" alt="Image" src="https://github.com/user-attachments/assets/06bba0e1-0afd-43f6-acf5-916c96662b6d" />
<img width="1078" height="407" alt="Image" src="https://github.com/user-attachments/assets/646121cb-50f6-43df-ae84-b695eb4ee4d7" />

<img width="997" height="397" alt="Image" src="https://github.com/user-attachments/assets/e2c1e70b-1d48-4740-ae4e-ef2ca357404e" />
<img width="1321" height="673" alt="Image" src="https://github.com/user-attachments/assets/06bba0e1-0afd-43f6-acf5-916c96662b6d" />
<img width="1078" height="407" alt="Image" src="https://github.com/user-attachments/assets/646121cb-50f6-43df-ae84-b695eb4ee4d7" />
