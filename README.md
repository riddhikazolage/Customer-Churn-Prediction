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
I preprocessed the dataset (scaling continuous features with `StandardScaler` and encoding categorical variables with `get_dummies`) and trained two classification algorithms to evaluate baseline performance.

### Model Performance Comparison:
| Model Name | Accuracy | ROC-AUC |
| :--- | :--- | :--- |
| **Logistic Regression (Winner)** | **80.2%** | **0.842** |
| Random Forest Classifier | 78.9% | 0.829 |

### 🔍 Top Feature Importances (What Drives Churn)
By extracting model coefficients, the top factors driving a customer to leave are:
1. **Internet Service (Fiber Optic):** Strongest positive correlation with churn behavior.
2. **Payment Method (Electronic Check):** High correlation with churn.
3. **Paperless Billing (Yes):** Customers with paperless billing show higher churn probability.

## 🚀 Key Takeaway for Business
The Logistic Regression model correctly predicts customer trends with **80.2% accuracy**. Telecom businesses can utilize this model to automatically flag high-risk accounts (specifically targeting fiber-optic users on month-to-month terms) and offer proactive loyalty discounts or contract optimization before they officially churn.
