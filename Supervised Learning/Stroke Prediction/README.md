
# 🧠 Stroke Prediction Using Machine Learning

This project aims to predict the likelihood of a person having a stroke based on medical and lifestyle features such as age, hypertension, heart disease, smoking status, and more. The goal is to build a classification model that helps in early detection and prevention of stroke risks.

## 📁 Dataset Information
Source: Kaggle / Open Healthcare Dataset

### Target Clumn: stroke (0 = No stroke, 1 = Stroke)

Features:
gender, age, hypertension, heart_disease, ever_married,
work_type, Residence_type, avg_glucose_level, bmi, smoking_status
(and more...)

### 🧪 Technologies & Tools Used
Python 🐍,Pandas, NumPy,
Matplotlib, Seaborn (Data Visualization)
Scikit-learn
XGBoost
Joblib (Model Saving)
Jupyter Notebook

### 📊 Exploratory Data Analysis (EDA)
Checked for null and duplicate values
Handled missing data using mode and mean imputation
Handled imbalanced dataset using oversampling (SMOTE/resampling)

### Performed feature scaling using:

Standardization
Normalization
Visualized:
Class distribution
Correlation heatmap
Distribution of stroke probabilities

## 🤖 Machine Learning Models Used
Model	Accuracy
DecisionTree Classifier ~ 96%
Logistic Regression	~76%
XGBoost Classifier	~97%
Random Forest Classifier	✅ 98.82% (Best)

### Also evaluated using:

Confusion Matrix
Precision, Recall, F1 Score
ROC AUC Curve

### 💾 Model Deployment
Final trained model (Random Forest) saved using joblib as stroke_model.pkl

Can be easily loaded and used for future predictions.