📊 Analyzing Child Cancer Healthcare Data

📌 Project Overview

This project analyzes healthcare expenditure data for children with cancer to understand utilization, costs, and financial burdens. It involves:

Data loading, cleaning, and transformation

Statistical summaries of numerical and categorical variables

Exploratory Data Analysis (EDA) with visualizations

Predictive modeling to identify key drivers of financial burden

The goal is to provide insights into the economic challenges faced by families with children battling cancer.

⚙️ Tech Stack
Python (Data analysis & modeling)

Libraries:

NumPy – numerical operations

Pandas – data manipulation

Matplotlib & Seaborn – visualization

Scikit-learn – preprocessing & machine learning

📂 Data Sources
Raw healthcare expenditure data (Excel files, 2019–2023)

Cancer-specific datasets merged with demographic and financial indicators

Key variables include:

Age, Insurance Status, Perceived Health Status

Healthcare Expenditures, Out-of-Pocket Payments, Family Income

Poverty Status, Hospital Nights, Prescribed Medicines, Office Visits

🔄 Workflow
Data Loading – Import Excel sheets, merge cancer-specific records

Data Wrangling – Rename columns, handle duplicates, create indicators

Feature Engineering –

Financial burden indicator (OOP > 9% of family income)

Age grouping (Baby/Toddler, Kid, Teenage, Adult, Old)

Poverty & insurance status mapping

Exploratory Data Analysis (EDA) –

Statistical summaries (numerical & categorical)

Correlation heatmaps, histograms, scatter plots, bar charts

Financial burden analysis across age, poverty, insurance, health status

Modeling –

Random Forest Classifier to predict financial burden

Feature importance ranking

StandardScaler applied for numerical features

📊 Key Visualizations
Correlation heatmap of healthcare variables

Age distribution histogram

Family income distribution histogram

Financial burden by age group & poverty status

Scatter plot: Family income vs. Out-of-Pocket payments (log scale)

Multi-panel analysis of financial burden across categorical & numerical variables

🤖 Machine Learning Insights
Random Forest Classifier identifies top predictors of financial burden.

Features with highest importance:

Family income

Out-of-pocket payments

Insurance status

Poverty category

