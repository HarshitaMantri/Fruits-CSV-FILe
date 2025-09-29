# Fruits-CSV-File
📁 File Name

fruit_sales.csv

📝 Description

This dataset contains sample sales data of various fruits sold over a period of three days. It includes details like the fruit name, quantity sold, price per unit, and total revenue generated. It can be used for learning data analysis, data visualization, or testing Python scripts using libraries such as pandas.

📊 Columns Explained
Column Name	Description
Date	The date of the sale in YYYY-MM-DD format
Fruit	The type of fruit sold
Category	Fruit category (e.g., Citrus, Pome, etc.)
Quantity Sold	Number of units sold
Unit Price	Price per unit (in USD)
Total Sales	Total revenue = Quantity Sold × Unit Price
🧪 Sample Data
Date	Fruit	Category	Quantity Sold	Unit Price	Total Sales
2025-09-01	Apple	Pome	50	0.50	25.00
2025-09-01	Banana	Tropical	100	0.30	30.00
🔍 Possible Use Cases

🧮 Data analysis with pandas

📊 Plotting fruit sales trends

💾 Practice for data preprocessing and cleaning

🛠️ Machine learning feature exploration

✅ Getting Started with Python
import pandas as pd

# Load dataset
df = pd.read_csv("fruit_sales.csv")

# Total sales per fruit
print(df.groupby("Fruit")["Total Sales"].sum())
