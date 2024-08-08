# Customer_churn_comapny_project
`ecommerce-analytics-solution`


Project Description

This project was undertaken to provide an end-to-end analytical solution for an e-commerce startup that previously managed its data using disparate formats like Excel, CSV, and flat files. The solution includes:

Developing a centralized data warehouse.
Creating an ETL (Extract, Transform, Load) pipeline.
Building dashboards to visualize key performance metrics.
Implementing machine learning models to predict customer churn and provide actionable insights.
Directory Structure


ecommerce-analytics-solution/
│
├── data/
│   ├── raw/
│   │   ├── sales_data.csv
│   │   ├── orders_data.csv
│   │   ├── customer_data.csv
│   │   └── churn_data.csv
│   └── processed/
│       ├── sales_data_cleaned.csv
│       ├── orders_data_cleaned.csv
│       ├── customer_data_cleaned.csv
│       └── churn_data_cleaned.csv
│
├── etl/
│   ├── extract.py
│   ├── transform.py
│   └── load.py
│
├── analysis/
│   ├── sales_analysis.ipynb
│   ├── orders_analysis.ipynb
│   ├── customer_analysis.ipynb
│   └── churn_analysis.ipynb
│
├── dashboards/
│   ├── sales_dashboard.twb
│   ├── orders_dashboard.twb
│   ├── customer_dashboard.twb
│   └── churn_dashboard.twb
│
├── docs/
│   ├── requirements.md
│   ├── design.md
│   └── user_guide.md
│
├── scripts/
│   ├── generate_sample_data.py
│   ├── start_etl.sh
│   └── setup_environment.sh
│
├── tests/
│   ├── test_extract.py
│   ├── test_transform.py
│   └── test_load.py
│
├── .gitignore
├── README.md
└── requirements.txt
Project Roles and Responsibilities

Data Analyst Role
Key responsibilities in this project included:

Requirement gathering and technical documentation.
Building an enterprise data warehouse using SSIS (SQL Server Integration Services).
Data preprocessing and analysis using Python libraries (Pandas, NumPy, Matplotlib, and Plotly).
Creating interactive dashboards with Tableau and PowerBI.
Implementing machine learning models for predicting customer churn.
Data Sources

The project utilized the following data sources:

Sales data
Orders data
Customer data
Churn data
Finance data
Products data
Tools and Technologies




