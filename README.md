# 🚲 Bike Sales Data Analysis & Cleaning

This repository contains a Python-based data analysis project focused on cleaning and visualizing raw bike sales data. The project demonstrates how to handle missing values, perform exploratory data analysis (EDA), and generate automated visual reports.

## 📊 Project Overview
The analysis processes a dataset of bike sales (originally `uncleaned bike sales data.xlsx`) to extract business insights regarding customer demographics, regional performance, and profitability.

## 🛠️ Tech Stack
- **Python**: Core programming language.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For handling numerical operations.
- **Matplotlib**: For creating static, animated, and interactive visualizations.

## 🧹 Data Cleaning Process
The notebook implements a robust cleaning pipeline to prepare the raw data for analysis:
- **Missing Value Handling**: Automatically fills missing entries in the `Day` column (using mean) and `Order_Quantity` column (using median).
- **Data Standardization**: Ensures columns like `Age_Group` and `Customer_Gender` are ready for grouping.
- **Export**: The final cleaned dataset is exported as `data.csv` for use in other BI tools like Tableau or Power BI.

## 📈 Key Features
- **Global Sales Tracking**: Analysis of sales across multiple countries including the US, UK, Australia, Germany, and Canada.
- **Profitability Metrics**: Calculations for `Revenue`, `Cost`, and `Profit` per transaction.
- **Dynamic Search & Plot Function**: A custom Python function that allows users to:
  1. Search for specific items in any column (e.g., searching for a specific 'Country' or 'Product').
  2. Automatically generate a bar chart showing the **Total Revenue by Product** for that specific search criteria.
