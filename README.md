
💳 Credit Card Fraud Detection

📌 Overview

This project aims to detect fraudulent credit card transactions using machine learning. Due to the highly imbalanced nature of fraud datasets (very few fraud cases compared to legitimate ones), special techniques such as oversampling and anomaly detection are applied to improve accuracy.

![image](https://github.com/user-attachments/assets/511b6dc4-188d-47cc-be0d-fe502d66c2f2)

🎯 Project Objectives

1.Detect Fraudulent Transactions:
Accurately identify credit card transactions that are potentially fraudulent based on historical data.

2.Handle Imbalanced Data:
Address the issue of class imbalance using techniques like SMOTE to ensure the model is sensitive to rare fraud cases.

3.Apply Machine Learning Models:
Train and evaluate multiple machine learning algorithms (e.g., Logistic Regression, Random Forest, XGBoost) to compare performance.

4.Feature Engineering & Scaling:
Analyze and preprocess input features (e.g., Amount, Time, PCA components) to optimize model performance.

5.Evaluate with Relevant Metrics:
Use precision, recall, F1-score, confusion matrix, and ROC-AUC to assess how well the model identifies fraud cases.

6.Build a Generalizable Pipeline:
Create a reusable and scalable pipeline for fraud detection that can be adapted to new data.

7.Minimize False Negatives:
Ensure that the model minimizes the chance of failing to detect actual frauds (which can be very costly).



⚙️ Techniques Used

A.Data preprocessing and feature scaling

B.Class balancing using SMOTE

C.Machine learning models:

1.Logistic Regression

2.Random Forest

3.XGBoost

D.Evaluation metrics:

1.Confusion Matrix

2.Precision, Recall, F1-Score

3.ROC-AUC Curve


![image](https://github.com/user-attachments/assets/fb23c261-bfdd-4608-8c42-e87517c43bf1)


📈 Results

After training and evaluating various models, the Random Forest and XGBoost classifiers outperformed others in terms of accuracy and fraud detection capability.

Using SMOTE to balance the dataset significantly improved recall and F1-score for the minority class (fraud).

Key evaluation metrics on the test set:

Precision (Fraud Class): ~0.91

AUPRC Score: 0.8412

F1-Score: ~0.90

ROC-AUC Score: ~0.97

Scale pos weight: 577.2868020304569

The model successfully identified the majority of fraudulent transactions with minimal false positives.

🧾 Conclusion

This project demonstrates that machine learning models, especially ensemble methods like Random Forest and XGBoost, can effectively detect credit card fraud when combined with appropriate preprocessing and balancing techniques. Handling data imbalance with SMOTE and evaluating the model using precision, recall, and ROC-AUC ensures reliable fraud detection. While the model performs well on historical data, deploying it in real-world systems would require continuous monitoring and periodic retraining with new data for optimal performance.


