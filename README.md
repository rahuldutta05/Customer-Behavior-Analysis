# Customer Behavior Analysis

## Description

This repository provides a comprehensive analysis of customer shopping behavior to uncover key purchasing patterns and demographic insights. By examining a dataset of 3900 customer records, the project aims to understand how variables such as age, gender, location, season, and payment methods influence purchasing decisions and purchase amounts. 

The analysis is divided into two main components:
1. **Data Preprocessing & Exploratory Data Analysis (EDA)**: Conducted in Python using Jupyter Notebooks to clean the data (e.g., handling missing review ratings) and explore initial statistics.
2. **Interactive Visualization**: A Power BI dashboard designed to present these insights dynamically, allowing stakeholders to easily filter and explore the customer behavior metrics.

## Files

- **`customer_shopping_behavior.csv`**: The primary dataset containing 3900 records of customer shopping behavior. It includes information such as Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount, Location, Size, Color, Season, Review Rating, Subscription Status, Shipping Type, Discount Applied, Promo Code Used, Previous Purchases, Payment Method, and Frequency of Purchases.
- **`notebook.ipynb`**: A Jupyter Notebook containing the data analysis pipeline. It loads the dataset using pandas, explores the data structure and statistics, handles missing values (such as filling missing `Review Rating` based on category medians), and performs other data preprocessing steps.
- **`customer_behavior_dashbaord.pbix`**: A Power BI dashboard file that likely provides interactive visualizations and insights derived from the customer shopping behavior dataset.

## Usage

1. Open `notebook.ipynb` in Jupyter Notebook or JupyterLab to view the data analysis and preprocessing steps.
2. Open `customer_behavior_dashbaord.pbix` using Microsoft Power BI Desktop to interact with the visualizations.
