# Project Title: AI-Driven Market Analysis for Best Laptop Deals

# Description:
In this project, I conducted an in-depth analysis of a comprehensive dataset related to laptop specifications and prices. The main objective was to develop an intelligent system capable of providing valuable insights to users seeking the best laptop deals in the market.

The project began with Exploratory Data Analysis (EDA) to gain a thorough understanding of the dataset. I performed univariate and bivariate analyses, carefully examining the distributions and relationships between various features. To ensure robust modeling, I addressed data skewness, class imbalances, and missing values using appropriate techniques.

Furthermore, I leveraged feature engineering to extract meaningful information from unstructured data present in certain columns. By creating new features and removing redundant ones, I enhanced the dataset's predictive power.

Handling categorical data, I employed one-hot encoding through a Column Transformer, effectively converting non-numeric attributes into suitable numerical representations.

Next, I ventured into training several machine learning algorithms, including linear regression, ridge regression, lasso regression, k-nearest neighbors regressor, support vector machine regressor, decision trees, random forest, XGBoost, gradient boost, voting regressor, and stacking. To streamline the process and ensure reproducibility, I encapsulated the data preprocessing and modeling steps into a comprehensive pipeline.

In order to determine the best-performing algorithm, I evaluated each model's performance using appropriate metrics. After identifying the most suitable one, I saved the pipeline and dataset in pickle format, enabling seamless model deployment.

To bring the power of this predictive model to the public, I created an intuitive web application using Streamlit to access the AI-driven laptop market analysis tool, making informed decisions on laptop purchases based on the model's recommendations.
