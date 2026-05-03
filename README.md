# Data Cleaning & Preprocessing

## Overview

This project focuses on cleaning and preparing a raw dataset for analysis. Real-world data often contains missing values, duplicate records, and inconsistent formats, which must be addressed before any meaningful analysis can be performed.

## Objectives

* Load and inspect the dataset
* Identify and handle missing values
* Remove duplicate records
* Standardize inconsistent data formats
* Prepare the dataset for further analysis

## Process

### 1. Data Inspection

* Used `.head()`, `.info()`, and `.describe()` to understand structure and data types

### 2. Handling Missing Values

* Identified null values using `.isnull()`
* Applied appropriate strategies such as removal or imputation

### 3. Removing Duplicates

* Checked for duplicate rows using `.duplicated()`
* Removed duplicates to ensure data accuracy

### 4. Data Standardization

* Cleaned and standardized inconsistent entries (e.g., text formatting, categories)
* Ensured uniform structure across the dataset

### 5. Data Validation

* Rechecked dataset after cleaning to confirm no remaining issues

## Tools & Technologies

* Python
* pandas
* Jupyter Notebook

## Outcome

The dataset was successfully cleaned and structured, making it reliable and ready for exploratory data analysis and machine learning tasks.

## File

* `01_Data_Cleaning.ipynb`

## Project Context

This project is part of a broader Data Analytics internship, demonstrating practical data preprocessing techniques used in real-world scenarios.

