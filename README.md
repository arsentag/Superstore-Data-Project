# Superstore-Data-Project
## Project Overview
This project involves the analysis and modeling of Superstore Sales Data, sourced from the "Sample Data" section on Tableau Public. The dataset provides insights into sales, profit, customer behavior, and regional performance, making it an excellent case study for exploratory data analysis (EDA), feature engineering, and predictive modeling.
The project is divided into three main phases:
- Data Collection and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Modeling and Evaluation
- Dashboard developed using Tableau

## Dataset
Source: https://public.tableau.com/app/learn/sample-data
### Dataset Description:
- Rows: 9994
- Columns: 21 (e.g. Order ID, Sales, Profit, Category, Region, Quantity, Discount)
- Purpose: Analyze business performance and build predictive models.

## Files and Structure
### Notebooks:
1. Data_Collection_and_Preprocessing.ipynb
- Cleans and preprocesses the dataset.
- Generates engineered features and prepares data for modeling.
2. EDA_Notebook.ipynb
- Performs exploratory data analysis with descriptive statistics and visualizations.
- Examines trends, category performance, and discount impacts.
3. Modeling_Notebook.ipynb
- Implements regression models, classification models, and clustering.
- Evaluates model performance and interprets clustering results.
### Datasets:
- superstore_data.xls: Initial dataset from Tableau Public
- superstore_data.csv: Cleaned and preprocessed dataset for EDA
- superstore_data_for_ml.csv: Cleaned and preprocessed dataset (encoded and scaled) for ML models.

## Results
### Key Findings:
- Time Trends: Sales peaked in specific months, indicating seasonal demand patterns.
- Category Insights: Technology generated the highest profit, while Furniture underperformed.
- Discount-Driven Losses: High discounts often reduced profitability, with variations across categories.
### Best Performing Models:
- Regression: Random Forest Regressor explained 46% of the variance in sales predictions.
- Classification: Random Forest Classifier achieved an F1 Score of 0.59 for profitability classification.
- Clustering: K-Means identified three distinct clusters based on sales and profit characteristics.

## Future Work
- Expand clustering analysis with hierarchical clustering for more granular segmentation.
- Integrate advanced regression models (e.g., XGBoost) to improve sales prediction accuracy.

## License
This project is licensed under the MIT License.









