🏷️ Nike Sales Data Analysis Project
📌 Project Overview

This repository contains a cleaned and structured Nike Sales dataset prepared for advanced data analysis and machine learning applications.

The primary objective of this project is to transform raw sales data into a high-quality analytical dataset suitable for:

📊 Exploratory Data Analysis (EDA)

📈 Business Intelligence Reporting

🤖 Machine Learning Modeling

📉 Sales Forecasting

🧠 Customer Insights & Segmentation

🎯 Business Problem

Retail organizations generate massive amounts of transactional data. However, raw datasets often contain:

Missing values

Inconsistent formatting

Duplicate entries

Incorrect data types

Noise and outliers

This project focuses on preparing a production-ready dataset that enables accurate analysis and reliable predictive modeling.

📂 Repository Structure
├── data/
│   ├── Nike_Sales_Uncleaned.csv
│   └── Nike_Sales_Cleaned.csv
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── README.md
└── requirements.txt

(Modify structure if different.)

🧹 Data Cleaning & Preprocessing Pipeline

The following structured preprocessing workflow was implemented:

1️⃣ Data Inspection

Checked dataset shape

Identified missing values

Reviewed data types

Performed statistical summary

2️⃣ Data Cleaning

Removed duplicate records

Standardized column names (lowercase, underscores)

Trimmed whitespace in string columns

Handled null values using:

Mean/Median imputation (numerical)

Mode/Category replacement (categorical)

3️⃣ Data Transformation

Converted date columns to datetime format

Extracted new features (Year, Month, Quarter)

Ensured correct numeric formatting

Encoded categorical variables (if required)

4️⃣ Data Validation

Verified final dataset consistency

Confirmed no missing critical fields

Checked for logical errors in values

📊 Dataset Description
Column Name	Description
Order_ID	Unique transaction identifier
Product	Product name
Category	Product category
Region	Sales region
Sales	Revenue generated
Profit	Profit earned
Quantity	Units sold
Order_Date	Transaction date

(Update according to actual dataset columns.)

📈 Exploratory Data Analysis (Possible Insights)

The cleaned dataset enables analysis such as:

📅 Monthly and yearly sales trends

🌍 Region-wise performance comparison

🏆 Top-selling products

💰 Profit margin analysis

📦 Category contribution to revenue

📉 Sales seasonality patterns

🤖 Machine Learning Use Cases

This dataset can support:

Sales forecasting (Regression models)

Demand prediction

Customer segmentation (Clustering)

Profit prediction

Time series forecasting

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

Jupyter Notebook

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/yourusername/nike-sales-analysis.git
cd nike-sales-analysis
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Load the Dataset
import pandas as pd

df = pd.read_csv("data/Nike_Sales_Cleaned.csv")
df.head()
📌 Key Highlights

✔ Cleaned and production-ready dataset
✔ Structured preprocessing workflow
✔ Ready for EDA and ML
✔ Scalable for real-world retail analysis

🔒 Data Usage Disclaimer

This dataset is intended strictly for:

Educational purposes

Portfolio projects

Practice and experimentation

It is not affiliated with or officially provided by Nike.
