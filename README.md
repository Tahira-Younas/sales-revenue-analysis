📊 Sales Revenue Analysis Project
Overview
This project analyzes an online retail dataset to uncover revenue trends across time, geography, and products. It includes data cleaning, feature engineering, and visualizations using Python libraries such as Pandas, Matplotlib, and Seaborn.

📁 Files Included
MonthR.png – Monthly revenue trend
YearR.png – Yearly revenue comparison
Top10C.png – Top 10 countries by revenue
Top10P.png – Top 10 products by revenue

🔍 Key Steps Data Cleaning
Removed missing values and negative quantities.
Replaced missing product descriptions with "Unknown Product".
Feature Engineering

Extracted date features 
Year, Month, Day, Weekday, Month-Year, and Week.
Calculated revenue as Quantity × UnitPrice.

Visualizations
Monthly Revenue: Line plot showing revenue trends over time.
Yearly Revenue: Bar chart comparing revenue across years.
Country-wise Revenue: Top 10 countries by total revenue.
Top Products: Top 10 products based on revenue.

📦 Tools & Libraries
pandas
matplotlib
seaborn
openpyxl

💡 Insights
The United Kingdom generated the highest revenue.
Revenue peaked in 2011, with a significant increase from 2010.
Certain products consistently contributed to high revenue.

🛠 How to Use
To replicate the analysis:
Clone the repository.
Place the dataset (Online Retail.xlsx) in the working directory.
Run the Python script (optional).
View the saved .png charts.
