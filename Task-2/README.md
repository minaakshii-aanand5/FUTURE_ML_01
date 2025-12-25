📊 Customer Churn Prediction System 📌 Project Overview

Customer churn is a critical challenge for banking and telecom businesses, as losing customers directly impacts revenue and long-term growth. This project focuses on analyzing customer behavior and building a machine learning–based churn prediction system to identify customers who are most likely to leave a service.

The solution combines data analysis, visualization, and predictive modeling to deliver actionable business insights and support data-driven decision-making.

🎯 Objectives

Analyze historical customer data to understand churn patterns

Identify key factors driving customer churn

Build a predictive model to estimate churn probability

Visualize insights using an interactive dashboard

Translate analytical findings into business recommendations

📂 Dataset

Source: Bank Customer Churn Dataset (Kaggle)

Size: 10,000 customer records

Target Variable: Exited (1 = Churned, 0 = Retained)

Key Features:

Demographics: Age, Gender, Geography

Financial: Credit Score, Balance, Estimated Salary

Behavioral: Number of Products, Tenure, Activity Status, Credit Card Ownership

🔍 Exploratory Data Analysis (EDA)

The EDA phase focused on understanding churn distribution and customer behavior across multiple dimensions:

Overall churn rate (~20%)

Churn by age group

Churn by geography (France, Germany, Spain)

Churn by activity status

Churn vs account balance

📊 Dashboard & Visualization

An interactive Power BI dashboard was developed to explore churn trends dynamically using slicers and filters. The dashboard highlights:

High-risk customer segments

Regional churn variations

Behavioral patterns linked to churn

Financial risk from high-balance customers

🤖 Machine Learning Model

A classification-based approach was used to predict customer churn.

Models & Techniques:

Logistic Regression

Random Forest Classifier

Feature scaling and encoding

Train-test split for validation

Evaluation Metrics:

Accuracy

Precision

Recall

Confusion Matrix

Classification Report

Feature Importance Insights:

High impact: Age, Number of Products, Credit Score, Balance, Tenure

Lower impact: Gender, Credit Card Ownership, Geography

📌 Key Business Insights

Approximately 1 in 5 customers churn, indicating a significant retention challenge

Churn increases sharply after age 40

Inactive customers show much higher churn rates

High-balance customers leaving pose direct financial risk

Behavioral and financial variables dominate churn prediction over demographics

🛠️ Tools & Technologies

Programming: Python (Pandas, NumPy, Scikit-learn)

Visualization: Power BI, Matplotlib

Environment: Google Colab

Data Handling: Google Sheets

Documentation: Google Docs, GitHub

📁 Repository Structure ├── data/ │ └── cleaned_dataset.csv ├── notebooks/ │ └── Project_2.ipynb ├── dashboard/ │ └── Project - 2 _ Dashboard.pbix ├── reports/ │ └── Project_2_Churn_Prediction.pdf └── README.md

🚀 Outcomes

Built an end-to-end churn analytics and prediction pipeline

Strengthened skills in EDA, feature engineering, ML modeling, and business storytelling

Demonstrated how analytics and AI can directly support customer retention strategy

📬 Author

Minakshi Aanand BS in Applied Artificial Intelligence & Data Science Aspiring Data Analyst | Machine Learning Enthusiast
