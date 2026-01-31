# Customer Churn Prediction using Machine Learning

Customer churn is a major challenge for subscription-based digital services, as losing existing customers directly impacts revenue.  
In this project, a machine learning model is built to predict whether a customer is likely to churn using demographic information, service usage patterns, subscription details, billing history, and customer support interactions.

The objective is to identify high-risk customers early so that businesses can take proactive steps to improve customer retention.

---

## Dataset

- **Dataset:** IBM Telco Customer Churn Dataset  
- **Source:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn  
- **Description:** A real-world inspired dataset published by IBM containing customer demographics, account information, service usage details, and churn labels.

---

## Machine Learning Approach

- **Learning Type:** Supervised Learning  
- **Problem Type:** Binary Classification  
- **Target Variable:** `Churn` (Yes / No)

---

## Project Pipeline

1. Data understanding and cleaning  
2. Exploratory Data Analysis (EDA) to identify churn patterns  
3. Feature engineering and encoding of categorical variables  
4. Train–test split  
5. Model training:
   - Logistic Regression (baseline model)
   - Random Forest (advanced model)
6. Model evaluation using:
   - Confusion Matrix
   - Precision, Recall, and F1-score
   - ROC-AUC
7. Feature importance analysis  
8. Business insights and retention recommendations  

---

## Key Findings

- Random Forest performed better than Logistic Regression, particularly in terms of recall.
- Customers with shorter tenure showed a higher likelihood of churn.
- Month-to-month contracts and higher monthly charges were strongly associated with increased churn.

---

## Technologies Used

- Python  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  

---

## Business Insights

- Early-stage customers form a high-risk churn segment.
- Encouraging customers to opt for long-term contracts can significantly reduce churn.
- Retention strategies should prioritize customers identified as high-risk by the model.

---

## License

This project is released under the **MIT License**.
