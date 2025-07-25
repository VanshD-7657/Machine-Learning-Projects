# 📉 Customer Churn Prediction Using Machine Learning

### 📌 Overview
This project aims to predict whether a customer will churn (leave the service) based on their demographic details, subscription plans, and service usage.

It uses exploratory data analysis (EDA), data preprocessing, and multiple machine learning models to identify key factors affecting churn.

### 📂 Dataset Information
Target Column: Churn (Yes / No)

 Features include:
Demographics: gender, SeniorCitizen, Partner, Dependents

Subscription: Contract, PaymentMethod, PaperlessBilling

Service Usage: InternetService, StreamingTV, OnlineSecurity, TechSupport

Numeric: tenure, MonthlyCharges, TotalCharges

🛠 Technologies Used
Python 🐍,
Pandas, NumPy (Data Handling),
Matplotlib, Seaborn (Visualization),
Scikit-learn (Model Building)

### 🔍 Exploratory Data Analysis (EDA)
✅ Checked missing values & data types
✅ Converted TotalCharges to numeric
✅ Visualized churn distribution (countplots, boxplots, histograms)
✅ Analyzed relationships between features & churn

### 🤖 Machine Learning Models Used
✅ Logistic Regression
✅ Random Forest Classifier
✅ XGBoost Classifier

### 📊 Model Evaluation Metrics:
Accuracy
Precision, Recall, F1-Score
Confusion Matrix
ROC-AUC Curve

### 📈 Results
Random Forest performed best with ~XX% Accuracy.

Important factors for churn: Contract, tenure, MonthlyCharges, InternetService.

### 📌 Future Improvements
🔹 Deploy using Flask/Streamlit
🔹 Hyperparameter tuning (GridSearchCV)
🔹 Feature importance using SHAP/LIME

### 👩‍💻 Author
Vansh Dhall
Aspiring Data Scientist | Python & ML Enthusiast