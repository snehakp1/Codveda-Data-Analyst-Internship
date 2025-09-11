# Codveda-Data-Analyst-Internship
# Customer Churn Prediction

This project aims to develop a **machine learning model** to predict **customer churn** (whether a customer will leave the company or not). Customer churn prediction is an essential task for businesses, especially in subscription-based services such as telecommunications, banking, and SaaS companies, as retaining existing customers is often more cost-effective than acquiring new ones.

##  Dataset
- The dataset is split into:
  - **Training Set (80%)** → Used to train machine learning models.
  - **Test Set (20%)** → Used to evaluate how well the trained model generalizes to unseen data.

Each row in the dataset represents a customer with multiple attributes (such as demographic details, service usage, account information, etc.), along with a target variable **`Churn`** indicating whether the customer left (Yes) or stayed (No).

##  Project Objectives
- Perform **data preprocessing** (handling missing values, encoding categorical variables, scaling, etc.).
- Conduct **exploratory data analysis (EDA)** to identify patterns and correlations related to churn.
- Train and evaluate multiple **machine learning models** (e.g., Logistic Regression, Decision Tree, Random Forest, XGBoost, Support Vector Machines).
- Compare models using metrics such as:
  - **Accuracy**
  - **Precision, Recall, F1-Score**
  - **ROC-AUC**
- Select the best model to predict churn effectively.

##  Expected Outcome
The final outcome will be a **churn prediction model** that can classify customers into “Churn” or “Not Churn.” This model can be used by businesses to:
- Identify customers at high risk of leaving.
- Take proactive retention measures (e.g., personalized offers, improved services).
- Reduce customer attrition and improve business profitability.