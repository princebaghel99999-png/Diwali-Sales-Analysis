Diwali Sales Analysis (EDA)

Exploratory Data Analysis on Diwali sales data using Python (Pandas, Matplotlib, Seaborn). The goal is to understand customer behaviour and find out which segments, regions and products drive the most sales.

Dataset

File: Diwali Sales Data.csv

Size: 11,251 rows x 15 columns (before cleaning)

Key columns: User_ID, Cust_name, Product_ID, Gender, Age Group, Age, Marital_Status, State, Zone, Occupation, Product_Category, Orders, Amount

Tools Used

Python
Pandas, NumPy
Matplotlib, Seaborn
Jupyter Notebook

Steps Followed

Data loading: read the CSV with unicode_escape encoding.

Data inspection: shape, info(), head(), describe().

Data cleaning

Dropped empty columns (Status, unnamed1).

Found 12 null values in Amount and dropped those rows (11,239 rows remain).

Changed Amount datatype from float to int.

Visualization: count plots and bar plots for Gender, Age Group, State, Marital Status, Occupation, Product Category and Product ID.

Key Insights

1. Gender vs Amount
   
   Females spent more than males.
   
   Female customers spent more than double the amount spent by male customers.

2. Age Group and Gender
   
   The 26-35 age group spent the most, in both males and females.
   
   The 36-45 age group spent less than 26-35.

   The 18-25 age group spent less than 36-45.
   
   The 0-17 and 55+ age groups spent the least.
   
3. State, Amount and Orders
   
   Uttar Pradesh, Maharashtra, Karnataka and Delhi spent the most.
   
   Madhya Pradesh and Andhra Pradesh had average spending.
   
   Himachal Pradesh, Haryana, Bihar and Gujarat spent the least.
   
4. Marital Status

   Married people spent more than single people.

   Married women spent the most.

   Single women spent less than married women.

   Males (both married and single) spent very little compared to females.
   
5. Occupation

   IT Sector, Healthcare, Aviation and Banking contributed the highest sales.
   
   Agriculture, Textile, Construction and Food Processing contributed the lowest sales.
   
   The remaining occupations had average spending.
   
6. Product Category
  
   Food had the highest spending.

   Clothing & Apparel, Electronics & Gadgets and Footwear & Shoes came next.

   Furniture, Games & Toys, Sports Products, Beauty, Auto and Stationery had the lowest spending.
  
8. Top Products

   The top 10 products by number of orders are shown in the notebook as a bar chart.
