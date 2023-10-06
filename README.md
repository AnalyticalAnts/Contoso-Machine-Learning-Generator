
# Contoso Machine Learning Data Generator

This Jupyter notebook provides an easy-to-use script to ingest common 'contoso' data files and output models for data scientists to use for modeling and demonstration purposes.

## Overview

- **Purpose**: To facilitate the creation of custom machine learning datasets based on either pre-defined scenarios or user-defined custom scenarios.
- **Tracks**: Users have two distinct options:
  1. Select pre-defined scenarios.
  2. Create their own custom scenarios, including forecasting, clustering, and different patterns.

## Pre-Defined Scenarios:

### 1. Age-based Spending Pattern Scenario:
   - **Age Groups and Spending Patterns**:
     - Ages 18-30: High spending on Electronics and Fashion.
     - Ages 31-45: Medium spending on Home Goods and Groceries.
     - Ages 46-60: Low spending on Groceries and Pharmaceuticals.
     - Ages 60+: Medium spending on Pharmaceuticals and Books.
   - **Shopping Patterns by Time-of-Day**: Younger groups shop late at night, while older groups shop during the day.
   - **Day-of-Week Shopping Patterns**: Younger groups shop more on weekends, older groups shop uniformly throughout the week.
   - **Preferred Communication Channels**: Younger groups prefer email/mobile notifications, older groups prefer direct mail/phone calls.

### 2. Rare-class Customer Identification:
   - A new customer attribute, "ValuableCustomer", labels a small subset of customers as valuable.
   - These customers exhibit:
     - Higher average order values.
     - Preference for premium products.
     - Frequent shopping intervals.
   - **Challenge**: Identify these valuable customers based on behaviors and attributes.

### 3. Seasonal Product Preferences:
   - Product sales data showcases seasonality: e.g., winter gear sales peak during cold months, while swimwear peaks during summer.
   - Dimension table may indicate the season for each product.
   - **Challenge**: Forecast sales and identify seasonal trends.

### 4. Store Performance Analysis:
   - Variability is introduced in store sales data, with some stores consistently outperforming others.
   - Dimension table attributes include store size, location type (mall vs. street), and staff count.
   - **Challenge**: Identify factors contributing to store performance.

## Features and Implementation Details:

- The notebook is built using libraries like pandas, numpy, and os.
- Various functionalities to load data, apply specific patterns, and export the modified data are provided.
- The generated datasets can be saved in multiple formats for further use.

## How to Use

1. Load your base dataset using the `load_data()` function.
2. Specify the desired parameters for data modification.
3. Use the `generate_custom_or_scenario_data()` function to produce the modified dataset.
4. Export the results using the `export_dataframes()` function to your desired format.

---

Note: For detailed instructions and understanding, it is recommended to go through the markdown sections in the notebook.
