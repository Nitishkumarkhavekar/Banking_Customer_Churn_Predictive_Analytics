# 🏦 Banking Customer Churn: Predictive Analytics & Risk Modeling

## 👋 Overview

Customer churn is a high-stakes challenge in the banking sector. This project utilizes a dataset of **10,000 customers** to identify key behavioral and demographic indicators that lead to account closure. By combining **Exploratory Data Analysis (EDA)** with **Machine Learning classification**, I developed a system that calculates the probability of churn, enabling the bank to deploy proactive retention strategies before the customer leaves.

## 🚀 Key Features & Analysis

  * **Predictive Modeling:** Developed and benchmarked multiple ML models, including **Logistic Regression, Decision Trees, Random Forest, and XGBoost**.
  * **Churn Probability Scoring:** Assigned a dynamic "Risk Score" to every customer to segment them into High, Medium, and Low risk.
  * **The "Early Warning System":** Specifically identified **"Gray-Zone" customers** (30%–70% churn probability)—the optimal group for targeted retention offers.
  * **Geographic & Demographic Insights:** Isolated significant churn variances across regions (e.g., Germany vs. France) and specific age brackets.
  * **Financial Profiling:** Analyzed the correlation between account balances, credit scores, and long-term customer loyalty.

## 🛠️ Technical Toolkit

  * **Languages & Libraries:** Python (**Pandas, NumPy**) for data engineering; **Scikit-Learn & XGBoost** for predictive modeling.
  * **Visual Intelligence:** **Seaborn & Matplotlib** for statistical distributions; **Power BI** for interactive executive dashboards.
  * **Data Engineering:** Addressed class imbalances (Churn vs. Non-Churn), utilized One-Hot Encoding, and implemented Feature Scaling.
  * **Model Evaluation:** Validated performance using **Confusion Matrices, ROC-AUC curves, and Precision-Recall metrics**.

## ⚙️ How It Works

1.  **Phase 1: EDA & Visualization** – Performed a deep-dive into customer demographics to find hidden patterns in attrition.
2.  **Phase 2: Feature Engineering** – Optimized the data by encoding variables and selecting high-impact features like Age, Tenure, and Balance.
3.  **Phase 3: Model Training** – Implemented a **Random Forest Classifier** which served as the primary engine for churn identification.
4.  **Phase 4: Risk Segmentation** – Exported model probabilities into a **Power BI "Risk Tracker"** for real-time managerial oversight.

## 📂 Project Structure

```plaintext
Banking-Churn-Prediction/
│── churn_dataset.csv            # Raw bank customer data (10k rows)
│── Churn_Analysis_Model.xlsx    # Excel-based EDA and preliminary profiling
│── Banking_Churn_ML.ipynb       # Full Python/Jupyter Notebook ML pipeline
│── Banking_Churn_Dashboard.pbix # Power BI interactive risk dashboard
└── README.md                    # Project documentation
```

## 📈 Key Business Insights

  * **The "Gray-Zone" Opportunity:** Targeting customers in the early-warning phase could potentially reduce churn by up to **20%**.
  * **Regional Variance:** Customers in specific European branches showed a **2x higher churn rate**, indicating a need for localized service improvements.
  * **Age Demographics:** Older customers (45–60) displayed a higher churn propensity, suggesting a requirement for tailored "Loyalty Products" for senior segments.
  * **Model Success:** The final XGBoost implementation achieved high accuracy in distinguishing "At-Risk" profiles from loyal customers.

## 🤝 Connect

💼 **LinkedIn:** [linkedin.com/in/nitishkumar-khavekar](https://www.google.com/search?q=https://www.linkedin.com/in/nitishkumar-khavekar)  
💻 **GitHub:** [github.com/Nitishkumarkhavekar](https://www.google.com/search?q=https://github.com/Nitishkumarkhavekar)
