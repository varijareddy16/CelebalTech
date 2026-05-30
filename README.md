        CELEBAL TECHNOLOGIES - WEEK 1 ASSIGNMENT SUMMARY

NAme   : N.Varija Reddy
Email      : varijareddyy@gmail.com
Dataset details:
Link       : https://www.kaggle.com/datasets/anvitkumar/shopping-dataset
File      : Combined_dataset.csv
Original   : 1000 rows x 24 columns
Final      : 1000 rows x 26 columns
Steps involved:
Step 1 - Loaded Dataset
         -> Loaded CSV using pd.read_csv()
         -> 1000 rows and 24 columns loaded successfully
Step 2 - Data Exploration
         -> Viewed head() and tail()
         -> Checked shape, columns and data types
Step 3 – Handleing Missing Values
         -> Identified nulls using isnull().sum()
         -> Numeric columns filled with median
         -> Text columns filled with Unknown
         -> Missing values remaining : 0
Step 4 - Basic Operations
         -> Filtered products with rating > 4
         -> Selected important columns for analysis
         -> Columns selected : title, category, rating,
            initial_price, discount, final_price, seller_name
Step 5 - Remove Duplicates
         -> Checked duplicates using duplicated().sum()
         -> Removed using drop_duplicates()
Step 6 - Derived Column
         -> Added quantity column assumed = 1
         -> Created total_amount = final_price x quantity
         -> New column added successfully
Step 7 - Save Cleaned Dataset
         -> Saved as shopping_cleaned.csv
         -> Final shape : 1000 rows x 26 columns
Results:
Final Rows           : 1000
Final Columns        : 26
Missing Values       : Filled with median and Unknown
Duplicates Removed   : Yes
New Column Added     : total_amount
Output File          : shopping_cleaned.csv

