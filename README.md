## 🏦 Credit Risk Analysis using Exploratory Data Analysis (EDA)
This project focuses on identifying drivers behind loan default using real-world data from a consumer finance company. It applies Exploratory Data Analysis (EDA) to understand which attributes in a loan applicant's profile contribute to default risk. The results of this analysis can guide better loan approval decisions.

## 📌 Problem Statement
Financial institutions often face the challenge of lending money to applicants with limited or no credit history. The goal is to identify patterns indicating whether an applicant is likely to default or not, thereby minimizing potential financial losses and improving lending efficiency.

## 🎯 Objectives
- Use EDA techniques to uncover patterns and relationships in loan data.
- Understand the impact of demographic and financial features on loan defaults.
- Identify top indicators for clients with payment difficulties.
- Deliver business-ready insights that can aid in risk-based loan decision-making.

## 🧾 Dataset Description
The dataset consists of the following files:

- `application_data.csv`: Client info at the time of loan application.
- `previous_application.csv`: Historical loan details of clients.
- `columns_description.csv`: Metadata of variables.

These datasets contain features like income type, contract type, loan amount, previous applications, etc., with the target variable indicating if a client has payment difficulties (defaulted).

## 🧠 Methodology
✔️ Task Breakdown:
- Task 1: Imported all required modules (Pandas, NumPy, Seaborn, Matplotlib).
- Task 2: Loaded and cleaned `application_data.csv`.
- Task 3: Explored data structure, types, and basic statistics.
- Task 4: Performed missing value analysis; removed columns with >40% missing data and imputed others using mean/mode.
- Task 5: Analyzed numerical and categorical features.
- Task 6: Conducted univariate analysis (histograms, bar charts).
- Task 7: Detected outliers using boxplots and business intuition.
- Task 8: Merged `application_data.csv` and `previous_application.csv` for richer analysis.
- Task 9: Performed bivariate analysis on important features vs target variable.



## 📊 Key Insights

- **Clients with payment difficulties** had lower credit income, higher loan amount, and specific contract types.
- Features like `NAME_INCOME_TYPE`, `CODE_GENDER`, `AMT_CREDIT`, `NAME_CONTRACT_TYPE` showed strong correlation with the target.
- Outliers were identified in features like `AMT_INCOME_TOTAL`, `CNT_CHILDREN`, etc., but were retained for analysis.
- Data imbalance was found (~8% defaulters); visualized using percentage plots for better clarity.
- Top 10 variable correlations were computed separately for defaulters and non-defaulters to understand behavior segmentation.



