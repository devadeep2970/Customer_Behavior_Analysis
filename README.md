# 📊 Customer Behavior Data Analytics Project

## 🔎 Overview

This project demonstrates an end-to-end data analytics workflow, transforming raw customer shopping data into meaningful business insights. The analysis includes data loading in Python, exploratory data analysis (EDA), data cleaning, SQL-based querying using PostgreSQL/MySQL/SQL Server, and building an interactive Power BI dashboard.

The objective is to analyze purchasing behavior, discount trends, and product performance to support data-driven business decisions.

 📁 Dataset

The dataset contains customer transaction details including:

* Customer ID
* Item Purchased
* Category
* Purchase Amount
* Discount Applied
* Payment Method
* Date of Purchase

The data was initially provided in CSV format and processed using Python before being loaded into a relational database.

 🛠 Tools & Technologies

* **Python (Pandas, NumPy)** – Data loading, cleaning, and EDA
* **Jupyter Notebook** – Analysis environment
* **SQL (PostgreSQL / MySQL / SQL Server)** – Querying and aggregation
* **SQLAlchemy** – Database connection
* **Power BI** – Interactive dashboard creation
* **Excel** – Data validation and intermediate checks
* **Gamma** – Presentation (PPT) creation
* **Git & GitHub** – Version control and documentation

 🔄 Project Steps

1. Loaded the dataset into Python using Pandas
2. Performed Exploratory Data Analysis (EDA)
3. Cleaned and standardized column values
4. Loaded cleaned data into SQL database
5. Executed SQL queries for business analysis

   * Conditional aggregation
   * Discount rate calculation
   * Category-wise ranking using window functions
6. Built Power BI dashboard for visualization
7. Created a summary report and presentation using Gamma

 📊 Dashboard

The Power BI dashboard includes:

* Category-wise sales analysis
* Top-performing products
* Discount usage trends
* KPI cards (Total Orders, Revenue, Discount Rate)
* Purchase distribution visuals

The dashboard enables stakeholders to quickly understand customer purchasing patterns and promotional effectiveness.

 📈 Results & Insights

* Identified products with high discount dependency
* Analyzed top-selling items within each category
* Measured discount rate percentages using SQL aggregation
* Generated actionable insights for pricing and marketing strategies

The project demonstrates strong skills in data transformation, SQL querying, and business intelligence reporting.

 ▶ How to Run

1. Clone the repository
2. Install required Python libraries:

   ```
   pip install pandas sqlalchemy psycopg2
   ```
3. Run the Jupyter Notebook for EDA and data cleaning
4. Configure database credentials and load data into SQL
5. Execute SQL queries for analysis
6. Open the Power BI (.pbix) file to view the dashboard

🎯 Key Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis
* SQL Window Functions & Aggregations
* Database Integration
* Data Visualization
* Business Insight Generation
* End-to-End Analytics Workflow

