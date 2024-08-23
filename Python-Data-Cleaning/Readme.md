# Lokii Data Analysis Project - Python Overview

## Project Overview
This segment of the Lokii Data Analysis Project focuses on data cleaning, preprocessing, and transformation using Python. The goal was to prepare the raw transactional data for further analysis and visualization while addressing inconsistencies, errors, and data quality issues.

## Data Structure Overview

The dataset represents retail transactional data taken from Kaggle  for a hypothetical clothing startup, Lokii. It includes comprehensive information about customers, their purchases, and transaction details. The key attributes in the dataset are:
Customer Information:
Customer ID, Name, Email, Phone, Address, City, State, Zipcode, Country
Age, Gender, Income, Customer Segment
Transaction Details:
Last Purchase Date, Total Purchases, Amount Spent
Product Information:
Product Category, Product Brand, Product Type
Additional Attributes:
Feedback, Shipping Method, Payment Method, Order Status
<img width="262" alt="Screenshot 2024-08-19 at 2 30 33 PM" src="https://github.com/user-attachments/assets/79eb4b69-0812-431e-bb3b-18688dfe6d16">


## Key Steps in Data Cleaning and Preprocessing

### Handling Missing Values:

Null Value Removal: Applied modal imputation for categorical data and mean imputation for numerical data where relevant. Irrelevant records were deleted.

### Data Type Conversion:

Ensured all data types were correctly formatted to facilitate accurate analysis. This included converting string dates to datetime objects, and numeric columns to the appropriate data types.
### Date Mismatch Correction:

Extracted the correct date values from the “Date” column and synchronized them with the “Month” and “Year” columns to correct discrepancies.
Correcting Inconsistent Location Data:

Monitored and adjusted incorrect city, state, and country values to maintain data integrity, ensuring that location-based insights would be reliable.
### Deduplication:

Removed duplicate transaction and customer IDs to maintain data accuracy, ensuring each record was unique and reflective of actual transactions.

## Conclusion
The data cleaning and preprocessing steps performed in Python were crucial in preparing the dataset for SQL analysis and Tableau visualization. The cleaned dataset now provides a strong foundation for generating actionable insights.

### Libraries used: Pandas, Numpy, matplotlib (for EDA)
