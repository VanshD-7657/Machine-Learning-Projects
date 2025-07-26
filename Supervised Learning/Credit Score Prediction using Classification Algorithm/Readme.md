Here’s a **professional README.md** for your **Credit Score Prediction (Classification)** project:

---

# 📊 Credit Score Prediction using Machine Learning

## 📌 Overview

This project predicts a customer's **Credit Score (Good / Standard / Poor)** based on their financial, credit, and behavioral details.
It uses **Classification Algorithms (Random Forest, Logistic Regression, Decision Tree)** and applies **SMOTE** to handle imbalanced data.

The **Random Forest Classifier** gave the **best accuracy** after hyperparameter tuning.

---

## 🚀 Features

✅ Data Preprocessing (Handling Missing Values, Encoding, Scaling)
✅ Exploratory Data Analysis (EDA) with visualizations
✅ Model Training using Logistic Regression, Decision Tree, Random Forest
✅ Handling Imbalanced Data with **SMOTE**
✅ Hyperparameter Tuning using **RandomizedSearchCV**
✅ Evaluation using Accuracy, Precision, Recall, F1-score
✅ Final Model Deployment for **Credit Score Prediction**

---

## 📂 Dataset Features

| Feature Name               | Description                            |
| -------------------------- | -------------------------------------- |
| Age                        | Age of the customer                    |
| Annual\_Income             | Total yearly income                    |
| Num\_Bank\_Accounts        | Number of bank accounts                |
| Num\_Credit\_Card          | Number of credit cards                 |
| Interest\_Rate             | Interest rate of loans                 |
| Num\_of\_Loan              | Number of active loans                 |
| Credit\_Mix                | Credit mix quality (Good/Bad/Standard) |
| Credit\_Utilization\_Ratio | Percentage of credit used              |
| Credit\_History\_Age       | Age of credit history                  |
| Payment\_Behaviour         | Pattern of payment                     |
| Credit\_Score (Target)     | Good / Standard / Poor                 |

---

## 🛠️ Technologies Used

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Scikit-Learn** (Random Forest, Logistic Regression, Decision Tree)
* **Imbalanced-learn (SMOTE)** for handling imbalanced classes
* **RandomizedSearchCV** for hyperparameter tuning
* **Joblib/Pickle** for model saving

---

## 🔍 Exploratory Data Analysis (EDA)

📊 Countplots, Histograms, Correlation Heatmaps
📊 Distribution of Credit Score across features
📊 Feature Importance using Random Forest

---

## 📈 Model Training

| Model               | Accuracy Before SMOTE | Accuracy After SMOTE |
| ------------------- | --------------------- | -------------------- |
| Logistic Regression | 30.2%                 | 60.6%                |
| Decision Tree       | 66.8%                 | 72.1%                |
| **Random Forest**   | **77.3%**             | **77.2%**            |

📌 **Random Forest achieved the best performance.**

---

## 🔮 Prediction Example

```python
# Predict Credit Score for new customer
new_customer = {
    "Age": [32],
    "Annual_Income": [600000],
    "Monthly_Inhand_Salary": [50000],
    "Num_Bank_Accounts": [3],
    "Num_Credit_Card": [2],
    "Interest_Rate": [12],
    "Num_of_Loan": [2],
    "Delay_from_due_date": [4],
    "Num_of_Delayed_Payment": [1],
    "Changed_Credit_Limit": [20000],
    "Num_Credit_Inquiries": [1],
    "Credit_Mix": ["Good"],
    "Outstanding_Debt": [150000],
    "Credit_Utilization_Ratio": [35.0],
    "Credit_History_Age": ["3 Years 6 Months"],
    "Payment_of_Min_Amount": ["Yes"],
    "Total_EMI_per_month": [8000],
    "Amount_invested_monthly": [10000],
    "Payment_Behaviour": ["High_spent_Small_value_payments"],
    "Monthly_Balance": [20000]
}

# Preprocess -> Scale -> Predict
pred = best_rf.predict(new_scaled)
print("Predicted Credit Score:", pred[0])
```

## 📌 Results

✅ **Random Forest achieved the highest accuracy (\~77%)**
✅ **SMOTE improved recall for minority classes**
✅ **Feature Importance analysis identified key financial indicators**


## 🎯 Future Improvements
🔹 Add **XGBoost / LightGBM / CatBoost** for better accuracy
🔹 Deploy model using **Flask / Streamlit**
🔹 Create an **interactive dashboard** for predictions

## 👨‍💻 Author
🔹 **Vansh Dhall** – [LinkedIn Profile](https://www.linkedin.com/in/vansh-dhall-703111363)
