# retail-data-engineering-capstone
Production-style batch processing data engineering project using PySpark for retail analytics.



Retail Systems
     ↓
Data Ingestion
     ↓
Data Lake
     ↓
PySpark Processing
     ↓
Gold Analytics Tables
     ↓
Power BI



## Dataset

This project uses the **Online Retail Dataset** available on Kaggle.

Dataset Source:
https://www.kaggle.com/datasets/carrie1/ecommerce-data

The dataset contains real-world retail transaction data including:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country



### Download Dataset

Install Kaggle CLI

pip install kaggle

Download dataset

kaggle datasets download carrie1/ecommerce-data

Unzip the file

unzip ecommerce-data.zip



### Project Folder Structure

After downloading, place the dataset inside the datasets folder.

Example structure:

retail-data-engineering-capstone

datasets/
    Online Retail.xlsx

notebooks/
    01_data_ingestion.py

-----------------------------------------------------------------------------------------
In your GitHub repo create the folder.
Add file → Create new file



