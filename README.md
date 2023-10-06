# Randomized Retail GL Generator
_Procured by Analytical Ants LLC_

This repository hosts a Python script that generates a randomized, yet logical, general ledger dataset tailored for retail businesses. It's a perfect tool for financial modeling training, educational purposes, and for anyone who needs a quick mock-up of a general ledger without diving deep into manual data entry.

## Features
- Generates ledger entries based on typical retail business transactions, such as sales, inventory purchases, expenses, and more.
- Ensures logical sequencing of transactions. For instance, a sale is often followed by a corresponding deduction in inventory.
- Randomized transaction dates within a span of the past two years, ensuring a realistic time flow.
- Incorporates descriptions for transactions to emulate real-world scenarios.
- Error handling in place to warn users if the output CSV file is already open.
- Maintains Accounting Integrity: The script ensures that the accounting equation (Assets = Liabilities + Owner's Equity) always holds true. Any discrepancy found is adjusted against the Owner's Equity account to ensure data integrity.

## Structure
The general ledger entries generated include the following fields:

- INDEX: A unique identifier for batches of entries.
- DATE: The date of the transaction.
- ACCOUNT: The account number.
- ACCOUNT DESCRIPTION: A brief descriptor of the account.
- DR (Debit): The debit amount, if any.
- CR (Credit): The credit amount, if any.

Every batch of entries is followed by a transaction description to provide context on the nature of the transaction.

## How to Use
1. Clone the repository.
2. Navigate to the directory containing the script.
3. Open and run the notebook: `Randomized Retail GL Generator.ipynb` using Jupyter Notebook or Jupyter Lab.
4. A CSV file named `Synthetic_Retail_GL_Data.csv` will be generated in the same directory with the randomized ledger entries.

## Resources
- [Jupyter Notebook with the Code](https://github.com/AnalyticalAnts/Randomized-Retail-GL-Generator/blob/main/Randomized%20Retail%20GL%20Generator.ipynb)
- [Generated Output Data (CSV)](https://github.com/AnalyticalAnts/Randomized-Retail-GL-Generator/blob/main/Synthetic_Retail_GL_Data.csv)

## Contribution
Feel free to fork this repository and make improvements or adapt the script to other industries or specific needs. Pull requests and enhancements are welcome!

## About Analytical Ants

**Analytical Ants** provides systems ("Ants") that systematically increase operational efficiencies and yields through dynamic data insights, data architecture, and processes. Our team takes pride in delivering these insights through a holistic approach encompassing a large portion of the data-pipeline, particularly emphasizing on warehousing, machine learning, and reporting.

### Our Core Services:

#### Warehousing and Machine Learning:
- Supervised & unsupervised ML data analysis.
- ML server integration.
- Star schema data modeling.
- Implementing enterprise data warehouse bus architecture.
- Server object scripting and scheduling (ETL).

#### Analysis Services & Reporting (PBI/Excel):
1. **Architectural Planning:** 
   - Server Selection (on-prem vs. premium).
   - Load Balancing.
   - Deployment Strategies.
   - Monitoring Tabular Solutions.
   - Security.
2. **Data Modeling:** 
   - Model Selection & Procurement.
   - Partitioning Strategies.
   - Model Optimizations.
   - Ingestion Strategies.
   - Relationship Design.
3. **Reporting:** 
   - Visualizations.
   - DAX optimizations.
   - JSON configurations.
   - Report Optimizations & Design.

### Let's Collaborate!
Whether you are just starting out in data analytics or looking to optimize your existing systems, our team at Analytical Ants is here to guide and support you. Connect with us today to partner in ‘Procuring Insights for YOUR Success’! For inquiries and potential collaborations, please [contact us](https://analyticalants.co/contact-us/)
–X
Text-to-Speech Reader
Choose a voice: 
Microsoft David - English (United States) (en-US)
 Read Selected Text Stop Reading

Speed: 
 3
