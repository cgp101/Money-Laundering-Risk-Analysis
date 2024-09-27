Overiew: 

This project provides a comprehensive analysis and prediction of money laundering risk using various machine learning models, SQL, and Tableau for interactive visualizations. 
The goal is to identify high-risk transactions and analyze how they differ across countries and industries. 
This repository includes SQL queries for feature engineering, data extraction, exploratory data analysis (EDA), model development, and optimized machine learning models. 
The risk predictions and transaction flows are visually represented in a Tableau dashboard.

Project Structure

    money-laundering-risk-prediction.ipynb: Kaggle notebook that contains all the steps from data loading, cleaning, feature engineering, and model building for money laundering risk prediction.
    Black_money_viz.csv: The dataset used for visualization in Tableau.
    Black_money.twb: Tableau workbook containing interactive visualizations, including Sankey diagram, risk analysis charts, and time-based transaction trends.

Clone this repository to your local machine using: git clone https://github.com/your-username/money-laundering-risk.git

Data Source

The dataset used in this project is sourced from Kaggle and covers transaction-level data, including transaction amounts, money laundering risk scores, industries involved, and details of shell companies and authorities reporting suspicious activities.

    Data Source Link: https://www.kaggle.com/datasets/waqi786/global-black-money-transactions-dataset

Steps Included:

    SQL Analysis:
        Extraction of transaction data by industry, country, and risk levels.
        Data aggregation and transformation for risk assessment and EDA.

    Exploratory Data Analysis (EDA):
        Initial data exploration using Python libraries like pandas and matplotlib.
        Visualizing transaction distributions, risk score trends, and detecting outliers.

    Feature Engineering:
        Creating new features from the raw data (e.g., Shell Companies Involved, Source of Money).
        Scaling and normalization of continuous variables.
        Handling missing values and data imputation.

    Modeling:
        Training and tuning machine learning models like Random Forest, XGBoost, and Logistic Regression for risk prediction.
        Cross-validation to select the best model based on accuracy, precision, and recall metrics.

    Model Fine-Tuning:
        Hyperparameter optimization using GridSearchCV.
        Feature importance analysis and model explainability.

    Tableau Visualizations:
        Created an interactive Tableau dashboard to visualize money laundering risk across countries and industries.
        Implemented Sankey diagrams to show transaction flows between nations.
        Developed time-series analysis charts to observe risk fluctuations over time.
        Bar and bubble charts for industry risk breakdown and shell company involvement.
## Check Out the Project:

- **Kaggle Notebook**: [Money Laundering Risk Prediction](https://www.kaggle.com/code/charit1011/money-laundering-risk-prediction)
- **Tableau Dashboard**: [Money Laundering Risk Analysis Dashboard](https://public.tableau.com/views/MoneyLaunderingRiskAnalysisPredictiveDashboard/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
