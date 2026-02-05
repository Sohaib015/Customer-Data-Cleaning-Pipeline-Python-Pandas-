# Customer-Data-Cleaning-Pipeline-Python-Pandas-
An end-to-end data cleaning pipeline built with python and pandas to transform messy customer dataset into a clean, analysis ready dataset. 

# Overview

This project demonstrates a complete data cleaning and preparation pipeline for a raw customer database using Python and pandas.
The goal is to take messy, real-world style customer data and transform it into a clean, analysis ready dataset by applying common data quality checks, cleaning techniques, and feature engineering steps.
This workflow reflects how data is typically prepared in real analytics and business environments before reporting or modeling.

# About the Dataset

The original raw dataset is not included in this repository.
This project focuses on demonstrating a reusable data cleaning pipeline, and the source data was either simulated or treated as private, similar to how real company data is often handled in production environments.
The cleaning logic is designed to work with any customer dataset that follows a similar structure.

# What This Project Covers
## The pipeline performs the following steps:
 - Initial data quality audit (duplicates, missing values, invalid entries)
 - Removal of duplicate customer records
 - Standardization of text fields (names, emails, cities, phone numbers)
 - Handling missing values with appropriate strategies
 - Filtering out invalid emails and unrealistic age values
 - Feature engineering for analytics:
 - Full customer name
 - Days since registration
 - Data quality flagging for incomplete profiles
 - Validation of cleaned vs raw data
 - Export of a final clean dataset

# Why This Matters

In real-world projects, raw data is rarely clean.

This project focuses on the most important stage of data analysis, preparing reliable and consistent data before insights or modeling work can happen.
The pipeline mirrors how data teams handle quality issues in production.

# Technologies Used

 - Python
 - pandas
 - NumPy

# Key Skills Demonstrated

 - Data quality assessment
 - Pandas data manipulation
 - Handling missing and inconsistent data
 - Feature engineering
 - Building structured data pipelines
 - Validation and sanity checks

# Author

Built as a practical data cleaning project to demonstrate real-world pandas workflows for data analytics.


