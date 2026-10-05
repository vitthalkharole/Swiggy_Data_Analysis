# 🍔 Swiggy Food Delivery Data Analysis

## 📌 Project Overview

This project analyzes Swiggy food delivery data to understand sales performance, customer ratings, ordering patterns, and geographical performance.

The analysis is performed using Python and focuses on transforming raw food-delivery data into meaningful business insights through data cleaning, exploratory data analysis (EDA), aggregation, and visualization.

The dataset contains **197,430 records and 10 columns**, covering information such as state, city, restaurant, location, food category, dish name, price, rating, rating count, and order date.

---

## 🎯 Business Objective

The primary objective of this project is to answer questions such as:

- How are sales distributed over time?
- Which days generate higher revenue?
- Which cities contribute the most to sales?
- How does revenue vary across states?
- What is the quarterly sales performance?
- What is the average customer rating?
- How does revenue differ between Veg and Non-Veg food?
- Which food categories and locations show stronger sales performance?

The analysis can help identify sales patterns and geographical opportunities that can support data-driven business decisions.

---

## 📊 Dataset

The analysis uses the `swiggy_data.xlsx` dataset.

### Dataset Dimensions

| Attribute | Value |
|---|---:|
| Records | 197,430 |
| Columns | 10 |

### Columns

| Column | Description |
|---|---|
| `State` | State where the order was placed |
| `City` | City where the order was placed |
| `Order Date` | Date of the order |
| `Restaurant Name` | Restaurant associated with the order |
| `Location` | Restaurant/order location |
| `Category` | Food/order category |
| `Dish Name` | Name of the dish |
| `Price (INR)` | Price of the ordered item |
| `Rating` | Customer rating |
| `Rating Count` | Number of ratings |

---

## 🛠️ Technology Stack

### Programming Language
- Python

### Libraries
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations and feature creation
- **Matplotlib** – Static visualizations
- **Seaborn** – Statistical visualization
- **Plotly Express** – Interactive visualizations

### Development Environment
- Jupyter Notebook

---

## 🔄 Project Workflow

```text
Raw Swiggy Dataset
        ↓
Data Loading
        ↓
Data Exploration
        ↓
Data Type Validation
        ↓
Data Cleaning & Transformation
        ↓
Feature Engineering
        ↓
KPI Analysis
        ↓
Exploratory Data Analysis
        ↓
Data Visualization
        ↓
Business Insights
