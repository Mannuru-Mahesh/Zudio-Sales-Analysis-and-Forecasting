Overview

This project presents an end-to-end Retail Sales Analysis and Sales Forecasting solution using the Zudio Sales Dataset. The objective is to analyze sales performance, identify key business trends, uncover revenue-driving factors, and build machine learning models to predict future sales.

The project covers the complete data analytics lifecycle, including data cleaning, exploratory data analysis (EDA), visualization, feature engineering, machine learning modeling, and business insights generation.

Dataset

Dataset Source:

https://www.kaggle.com/datasets/saketkshirsagar1/zudio-sales-test-dataset

The dataset contains retail sales information including:

* Product Category
* Clothing Type
* State
* Store Type
* Quantity Sold
* Price
* Revenue
* Sales Profit
* Staff Count
* Selling Area Size



Project Objectives

* Analyze overall sales performance
* Identify top-performing categories and products
* Evaluate state-wise revenue trends
* Analyze profit distribution
* Discover factors affecting sales
* Forecast future sales using Machine Learning
* Generate actionable business insights



Technology Stack

Programming Language

* Python

Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost (Optional)

Development Environment

* Jupyter Notebook
* VS Code

Project Workflow

1. Data Collection

* Imported sales dataset from Kaggle

2. Data Cleaning

* Removed duplicate records
* Handled missing values
* Validated data types

3. Feature Engineering

Created new business metrics such as:

Revenue = Price × Quantity

4. Exploratory Data Analysis (EDA)

Performed:

* Revenue Analysis
* Profit Analysis
* Category Analysis
* State-wise Sales Analysis
* Store Performance Analysis
* Monthly Sales Trends
* Correlation Analysis

5. Machine Learning

Implemented:

Sales Forecasting

* Random Forest Regressor
* XGBoost Regressor

 Model Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

6. Business Insights

Generated actionable recommendations based on sales trends and customer behavior.



Key Findings

* Kids category generated the highest revenue contribution.
* West Bengal emerged as the top-performing state.
* Revenue peaks were observed during festive seasons.
* Quantity sold had the strongest influence on revenue.
* Larger selling areas showed higher sales potential.
* Machine learning models successfully predicted future sales trends.


Project Structure


Zudio-Sales-Analysis-and-Forecasting
│
├── data
│   └── Zudio_sales_data.csv
│
├── notebooks
│   └── Zudio_Sales_Analysis.ipynb
│
├── src
│   ├── data_preprocessing.py
│   ├── eda.py
│   ├── sales_forecasting.py
│   ├── visualization.py
│   └── feature_importance.py
│
├── outputs
│   ├── charts
│   ├── reports
│   └── predictions
│
├── models
│   └── zudio_sales_model.pkl
│
├── requirements.txt
├── README.md
└── .gitignore


Installation

Clone the repository:

git clone https://github.com/your-username/Zudio-Sales-Analysis-and-Forecasting.git


Navigate to project folder:

cd Zudio-Sales-Analysis-and-Forecasting


Install dependencies:

pip install -r requirements.txt


Run the analysis:

python src/eda.py

Run forecasting model:

python src/sales_forecasting.py


Results

The project delivers:

* Comprehensive sales analysis
* Revenue and profit dashboards
* State-wise and category-wise insights
* Feature importance analysis
* Predictive sales forecasting model
* Business recommendations for decision-making


Future Improvements

* Power BI Dashboard Integration
* Tableau Visualization
* Customer Segmentation
* Recommendation System
* Sales Forecasting using Deep Learning
* Deployment using Streamlit


Author

Mannuru Mahesh

Aspiring Data Analyst | Python Developer | Machine Learning Enthusiast

If it's useful give a Star 

License

This project is intended for educational and portfolio purposes.
