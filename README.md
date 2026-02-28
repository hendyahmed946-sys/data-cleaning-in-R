

## 📌 Project Overview

This project focuses on cleaning, transforming, and preparing the Superstore Sales dataset for analysis and modeling.
The dataset contains transactional information about products, customers, and orders from a fictional retail company in the United States.

The goal is to ensure data quality, correct inconsistencies, handle missing values, and prepare structured datasets suitable for statistical analysis and machine learning.

---

## 📊 Dataset Description

The dataset includes variables such as:

* Order ID
* Customer ID
* Order Date
* Ship Date
* Ship Mode
* Segment
* Region
* Category
* Sub-Category
* Product Name
* Sales
* Quantity
* Profit
* Discount

---

## 🧹 Data Cleaning & Preparation Steps

The following steps were performed:

### 1️⃣ Data Import

* Read Excel sheets into R

### 2️⃣ Variable Type Validation

* Converted date variables to Date type
* Converted categorical variables to factors
* Ensured numeric variables were properly formatted

### 3️⃣ Data Cleaning

* Removed Country variable
* Corrected typos and inconsistencies
* Checked duplicates
* Standardized Region labels (W, E, C, N, S)

### 4️⃣ Missing Value Handling

* Identified missing values
* Applied appropriate imputation methods

### 5️⃣ Data Transformation

* Assigned customer names as row names
* Split data by Region
* Split data into:

  * Profit gained
  * Profit lost

### 6️⃣ Train/Test Split

* 70% Training
* 30% Testing

### 7️⃣ Statistical Analysis

* Mean Profit per Region
* Mean Sales per Region
* Descriptive statistics for high-value orders (>3000)

### 8️⃣ Custom Functions

Created:

* Numerical summary function (mean, median, variance, range, SD)
* Categorical summary function (mode + relative frequency table)

---

## 🛠 Tools & Libraries

* R
* dplyr
* tidyr
* readxl
* ggplot2

