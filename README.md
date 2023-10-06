# Contoso Machine Learning Generator (Beta)

This project provides data scientists, data engineers, and data analysts with a script to generate sample datasets for machine learning demonstrations. Using the famous Contoso dataset, the script produces enriched datasets suitable for modeling, ensuring that professionals can run demos without relying on real data. The generated datasets will be saved in the 'Modified Files' folder.

> **Beta Disclaimer**: This project is currently in beta. Features might change frequently, and there could be bugs. Please use with caution and feel free to report any issues you encounter.

## Table of Contents
- [How to Use](#how-to-use)
- [Features and Implementation Details](#features-and-implementation-details)
- [Resources](#resources)
- [Contribution, Feedback, and Bug Reporting](#contribution-feedback-and-bug-reporting)
- [About Analytical Ants](#about-analytical-ants)

## How to Use

1. Download (or clone) the repository: 
   - Terminal Command: git clone https://github.com/AnalyticalAnts/Contoso-Machine-Learning-Generator.git
   - or [Download ZIP](https://github.com/AnalyticalAnts/Contoso-Machine-Learning-Generator/archive/refs/heads/main.zip) from Github
2. Update 'USER PARAMETERS' found in the 'Contoso Machine Learning Generator.ipynb'
3. Press 'Run All' (visual studio code or your choice editor)
4. Files are loaded in the 'Modified Files' folder

A simple overview can be found here: [Youtube Tutorial](hyperlink)

## Features and Implementation Details
### Overview
- Users can select from predefined scenarios or create their own custom enrichments (i.e., Forecasting or Classification)
- Options are listed either to the right or below the input field
- Custom classifications also have 'patterns' which can be applied in addition to the classification (e.g., add classification, and then introduce seaonality to the respective data)
- Below are overviews on the different predefined scenarios

### Predefined Scenarios:
#### 1. Age-based Spending Pattern Scenario:
   - **Age Groups and Spending Patterns**:
     - Ages 18-30: High spending on Electronics and Fashion.
     - Ages 31-45: Medium spending on Home Goods and Groceries.
     - Ages 46-60: Low spending on Groceries and Pharmaceuticals.
     - Ages 60+: Medium spending on Pharmaceuticals and Books.
   - **Shopping Patterns by Time-of-Day**: Younger groups shop late at night, while older groups shop during the day.
   - **Day-of-Week Shopping Patterns**: Younger groups shop more on weekends, older groups shop uniformly throughout the week.
   - **Preferred Communication Channels**: Younger groups prefer email/mobile notifications, older groups prefer direct mail/phone calls.

#### 2. Rare-class Customer Identification:
   - A new customer attribute, "ValuableCustomer", labels a small subset of customers as valuable.
   - These customers exhibit:
     - increased order quantity.
     - additional increase and preference for premium products.
     - Frequent shopping intervals.
   - **Challenge**: Identify these valuable customers based on behaviors and attributes.

#### 3. Seasonal Product Preferences:
   - Product sales data showcases seasonality: e.g., winter gear sales peak during cold months, while swimwear peaks during summer.
   - Dimension table may indicate the season for each product.
   - **Challenge**: Forecast sales and identify seasonal trends.

### Implementation Details:

- The notebook is built using libraries like pandas, numpy, and os.
- Various functionalities to load data, apply specific patterns, and export the modified data are provided.
- The generated datasets can be saved in multiple formats: csv or pipe delimited
- You can load different Contoso files that are derived from [SQLBI's bak files](https://github.com/sql-bi/Contoso-Data-Generator)

## Resources
- Base files are based off [SQLBI's Contoso 10K.bak file](https://github.com/sql-bi/Contoso-Data-Generator)

## Contribution, Feedback, and Bug Reporting
As this project is in beta, we highly appreciate feedback. If you encounter any bugs or issues, please open an issue in this repository. Contributions and suggestions are welcome!

Feel free to fork this repository and make improvements or adapt the script to other industries or specific needs. Pull requests and enhancements are welcome!

## About Analytical Ants

**Analytical Ants** provides systems ("Ants") that systematically increase operational efficiencies and yields through dynamic data insights, data architecture, and processes. Our team takes pride in delivering these insights through a holistic approach encompassing Data Engineering, Data Science, and Data Analysis. 

### Let's Collaborate!
Whether you are just starting out in data analytics or looking to optimize your existing systems, our team at Analytical Ants is here to guide and support you. Connect with us today to partner in ‘Procuring Insights for YOUR Success’! For inquiries and potential collaborations, please [contact us](https://analyticalants.co/contact-us/)
