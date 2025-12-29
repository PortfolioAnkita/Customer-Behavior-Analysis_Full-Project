# Customer-Behavior-Analysis_Full-Project

📊 Customer Behavior Analysis Project
📌 Project Overview
This project analyzes customer shopping behavior to understand sales patterns, customer segments, and revenue drivers.
The complete analysis is done using Python, MySQL, and Power BI.
________________________________________
🛠 Tools & Technologies
•	Python (Pandas) – Data cleaning and preparation
•	MySQL – Solving business problems using SQL
•	Power BI – Dashboard and data visualization
________________________________________
📂 Project Workflow
1️⃣ Data Cleaning (Python)
•	Loaded dataset using pandas.read_csv()
•	Checked dataset using head(), info(), describe()
•	Identified missing values using isnull().sum()
•	Filled missing values
•	Prepared clean data for database
2️⃣ Data Analysis (MySQL)
•	Connected Python to MySQL using SQLAlchemy
•	Stored cleaned data into MySQL tables
•	Solved business questions such as:
o	Revenue by gender
o	Average spend by shipping type
o	Subscriber vs non-subscriber comparison
o	Top-rated products
o	Customer segmentation (New, Returning, Loyal)
o	Revenue contribution by age group
3️⃣ Dashboard Creation (Power BI)
•	Connected Power BI directly to MySQL
•	Created KPIs:
o	Total Customers
o	Average Purchase Amount
o	Average Review Rating
•	Built charts for:
o	Sales & revenue by category
o	Sales & revenue by age group
o	Subscription-based customer distribution
•	Added slicers for better interaction
•	Used dark theme background (#2A313B)
________________________________________
📈 Key Business Insights
•	Subscribed customers spend more
•	Clothing category performs best
•	Young adults generate highest sales
•	Loyal customers drive repeat revenue
________________________________________
📁 Repository Structure
├── Python Notebook (Data Cleaning)
├── SQL Queries (Business Problems)
├── Power BI Dashboard (.pbix)
├── Project Report
