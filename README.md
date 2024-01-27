Objective:
The objective of this project is to perform exploratory data analysis (EDA) on Diwali Sales Data to gain insights into the sales patterns, customer demographics, and popular product categories.
The analysis aims to provide a comprehensive understanding of the dataset and extract meaningful information that can be used for business decision-making.


Issues Found in Data:
1.	There were unrelated/blank columns ('Status', 'unnamed1') that were dropped.
2.	Null values were present in the dataset, and they were handled by dropping the corresponding rows.
3.	The data type of the 'Amount' column was converted to integer for further analysis.


Tools Used:
1. Python programming language
2. Libraries: NumPy, Pandas, Matplotlib, Seaborn


Data Cleaning Process:
1.	Imported necessary libraries for data analysis and visualization.
2.	Loaded the dataset ('Diwali Sales Data.csv') using Pandas.
3.	Explored the dataset's shape, information, and the first few rows to understand its structure.
4.	Dropped irrelevant columns ('Status', 'unnamed1').
5.	Checked for and handled null values.
6.	Converted the 'Amount' column to the integer data type.
7.	Performed descriptive statistics to understand the basic characteristics of the data.


Conclusion:
1.	Gender Analysis:
•	Females constitute the majority of buyers, and their purchasing power surpasses that of males.
2.	Age Analysis:
•	The age group of 26-35 years, particularly females, is the most prominent buyer segment.
3.	State Analysis:
•	Uttar Pradesh, Maharashtra, and Karnataka are the top states contributing significantly to both the number of orders and total sales.
4.	Marital Status Analysis:
•	Married women are the primary buyers, and they exhibit a higher purchasing power compared to other segments.
5.	Occupation Analysis:
•	IT, Healthcare, and Aviation sectors have the highest number of buyers.
6.	Product Category Analysis:
•	The most sold products are from Food, Clothing, and Electronics categories.
7.	Top Products:
•	Identified and visualized the top 10 most sold products.
