# Lokii-Data-Analysis-Project-

Data structure 

<img width="262" alt="Screenshot 2024-08-19 at 2 30 33 PM" src="https://github.com/user-attachments/assets/a9e6e0a8-080e-48c0-bc23-19386239fcd1">

The dataset represents retail transactional data taken from Kaggle. It includes comprehensive information about customers, their purchases, and transaction details. The key attributes in the dataset are:

Customer Information:
Customer ID, Name, Email, Phone, Address, City, State, Zipcode, Country
Age, Gender, Income, Customer Segment
Transaction Details:
Last Purchase Date, Total Purchases, Amount Spent
Product Information:
Product Category, Product Brand, Product Type
Additional Attributes:
Feedback, Shipping Method, Payment Method, Order Status
Data Issues and Inconsistencies
Upon initial inspection, several issues and inconsistencies were identified in the dataset:

Erroneous Values:

Date columns (Date, Month, Year) contained mismatched values, including future dates (up to December 2024).
Product categories and brands were incorrectly placed.
Age values were unrealistic or inconsistent.
Duplicate Entries:

Duplicate Transaction IDs and Customer IDs were found, which should be unique.
Data Discrepancies:

Incorrect city, state, and country combinations.
Incorrect data types, particularly for decimal values.
Missing Values:

Several columns contained null values that required imputation or removal.
Data Cleaning and Preparation Steps
To ensure the integrity and reliability of the dataset, the following cleaning steps were performed using Python:

Handling Missing Values:

Used mode imputation for categorical variables and mean imputation for numerical variables where relevant.
Irrelevant columns with a high proportion of missing data were removed.
Data Type Conversion:

Converted data types to ensure consistency, especially for numeric and date fields.
Date Mismatch Resolution:

Carefully extracted the correct date values from the "Date" column and synchronized the "Month" and "Year" columns accordingly.
City-State-Country Corrections:

Monitored and studied these columns together to detect and correct inconsistencies early on.
Duplicate Removal:

Identified and removed duplicate Transaction IDs and Customer IDs to ensure data uniqueness.
By addressing these issues, the dataset was transformed into a clean, reliable resource, ready for further analysis and visualization.
