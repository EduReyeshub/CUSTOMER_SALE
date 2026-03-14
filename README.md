# Customer Database Cleaning and Preparation

## Project Description

This project simulates a real-world data cleaning task commonly required in business environments. Many companies collect large amounts of customer data, but these datasets often contain missing values, duplicates, and inconsistent structures that make them difficult to use.

The objective of this project is to clean, organize, and prepare a customer dataset so it can be used effectively for analysis, reporting, or integration into business systems.

The final result of this project is a structured and clean Excel database that is ready for practical business use.

---

## Objectives

The main objectives of this project are:

- Inspect the dataset structure
- Identify missing or inconsistent values
- Remove duplicate records
- Organize and standardize column names
- Create a useful business metric (Total Spending)
- Deliver a clean and organized dataset in Excel format

---

## Dataset Information

The dataset used in this project contains customer demographic information and purchasing behavior data. Typical variables include:

- Customer ID
- Birth year
- Education level
- Marital status
- Income
- Product purchase information

The original dataset required cleaning before it could be used for analysis or operational purposes.

---

## Tools and Technologies

The following tools were used to complete this project:

- Python
- Pandas
- Google Colab
- Microsoft Excel

Python and Pandas were used for data inspection, cleaning, and transformation, while Excel was used to deliver the final organized dataset.

---

## Data Cleaning Process

The data preparation process followed these steps:

1. Initial data inspection using functions such as `head()` and `info()`
2. Identification of missing values in key columns
3. Removal of rows with missing income data
4. Detection and removal of duplicate records
5. Creation of a new feature called **Total_Spending**
6. Selection of relevant columns for the final dataset
7. Renaming columns to improve clarity
8. Sorting the dataset to identify high-value customers

---

## Final Deliverable

The final deliverable of this project is a cleaned and structured Excel dataset.

This file can be used for:

- Customer segmentation
- Marketing campaign preparation
- CRM database organization
- Business reporting

Final file:

clean_customer_database.xlsx

---

## Project Structure

customer-database-cleaning  
│  
├── marketing_campaign.csv  
├── clean_customer_database.xlsx  
├── data_cleaning_notebook.ipynb  
└── README.md  

---

## Conclusion

This project demonstrates a practical workflow for cleaning and preparing real-world datasets. The final output is a structured database that can be used directly for business analysis or operational processes.
