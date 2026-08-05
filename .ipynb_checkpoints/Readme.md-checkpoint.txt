# 📊 Customer Churn Prediction

A beginner-friendly Data Science  project that analyzes customer behavior and prepares data for predicting customer churn.

This project focuses on understanding the dataset through Exploratory Data Analysis (EDA) and preparing it for machine learning using feature engineering, encoding, scaling, and preprocessing pipelines.

---

## 🎯 Project Objective

The objective of this project is to analyze customer data and identify the factors that influence customer churn. The dataset is explored, preprocessed, and prepared for building machine learning classification models.

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── data/
│   └── customer_churn.csv
│
├── notebooks/
│   ├── 01_Exploratory_Data_Analysis.ipynb
│   ├── 02_Data_Preprocessing.ipynb
│
├── README.md
├── requirements.txt
```

---

## 📌 Dataset Features

- Plan Type
- Monthly Fee
- Average Weekly Usage Hours
- Support Tickets
- Payment Failures
- Tenure (Months)
- Last Login (Days Ago)
- Signup Date
- Churn (Target Variable)

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview
- Data type inspection
- Missing value analysis
- Duplicate value analysis
- Date feature extraction
- Univariate analysis
- Numerical feature analysis
- Categorical feature analysis
- Target variable analysis
- Numerical features vs Churn
- Categorical features vs Churn
- Correlation Heatmap
- Business Insights

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

- Converted `signup_date` into datetime format
- Extracted Signup Year, Month, and Day
- Removed unnecessary columns (`user_id`)
- Encoded the target variable (`Yes → 1`, `No → 0`)
- Performed Train-Test Split
- Applied One-Hot Encoding to the `plan_type` feature
- Standardized numerical features using `StandardScaler`
- Built a preprocessing pipeline using `ColumnTransformer` and `Pipeline`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Key Business Insights

Some important findings from the analysis include:

- Customer usage patterns influence churn.
- Customers with higher support tickets show different churn behavior.
- Plan type impacts customer retention.
- Customer engagement metrics such as tenure and login activity are useful predictors of churn.

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature selection
- Model deployment using Flask or FastAPI
- Interactive dashboard using Streamlit

---

## 👩‍💻 Author

**Anushka Sharma**

B.Tech CSE (Artificial Intelligence & Machine Learning)

Learning Machine Learning, Data Analysis, and AI Development.