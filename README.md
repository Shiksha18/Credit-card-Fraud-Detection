# Credit-card-Fraud-Detection
The notebook contains model for credit card fraud detection. The dataset was taken from Kaggle competition. To download dataset https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

S: Situation
In a project to detect credit card fraud, I was tasked with building a model to classify transactions as legitimate or fraudulent. The challenge lay in dealing with highly imbalanced data, as fraudulent transactions were significantly rarer than legitimate ones.

T: Task
The objective was to create a robust classification model capable of detecting fraud with high accuracy while minimizing false negatives, as missing fraudulent cases could lead to significant financial losses.

A: Action
To address data imbalance, I applied techniques like oversampling, undersampling, and Synthetic Minority Oversampling Technique (SMOTE) to balance the dataset. I experimented with multiple algorithms, including Logistic Regression, Decision Tree, and XGBoost, using Scikit-learn for implementation. After rigorous testing and hyperparameter tuning, XGBoost emerged as the best-performing model.

R: Result
The final model achieved a classification accuracy of 97%, effectively distinguishing between fraudulent and legitimate transactions. The use of SMOTE improved the detection of minority class (fraudulent cases), ensuring a balanced model performance. This project gave me exposure to handling imbalanced datasets and applying advanced classification techniques, enhancing my proficiency in machine learning tools and algorithms.
