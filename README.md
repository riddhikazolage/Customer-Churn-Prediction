# 📈 Customer Churn Prediction Model

## 📌 Project Overview & Business Problem
Customer churn happens when customers stop doing business with a company. In this project, I analyzed customer demographic, account, and behavioral data to build a predictive Machine Learning model. The goal is to help businesses identify high-risk customers early so they can take proactive retention steps.

## 🛠️ Data Stack & Libraries
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries used:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## 🔍 Key Data Insights & Exploratory Data Analysis (EDA)

During the analysis, I discovered three major drivers causing customer churn:
- **Contract Preference:** Customers on Month-to-Month contracts show a significantly higher churn rate compared to those on stable 1-year or 2-year contracts.
- **Tenure Vulnerability:** Customers with lower tenure (newer accounts) are highly susceptible to leaving, meaning onboarding retention strategies are critical.
- **Price Sensitivity:** Customers facing higher monthly charges tend to churn at a much faster rate, highlighting clear user price sensitivity.

## 🤖 Machine Learning Modeling & Results
I preprocessed the data (handling missing values, encoding categorical variables, and scaling features) and trained classification models to predict churn.
- **Models Evaluated:** Logistic Regression, Random Forest, or Support Vector Machine (SVM)
- **Final Model Performance:** Achieved an accuracy score of **[Insert your model accuracy, e.g., 82%]**.

## 🚀 Key Takeaway for Business
By deploying this predictive analytics model, companies can automatically flag high-risk customers and offer targeted discounts, better support, or contract upgrades to boost customer retention.
