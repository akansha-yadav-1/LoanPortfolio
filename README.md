# Loan Portfolio Management Analytics

## Overview
As a bank we would like to track how much amount is lent and to whom, for this I have created a Loan Portfolio Management Dashboard

The dashboard has 3 main tabs:
### 1. Loan Portfolio Overview
This gives an overall picture of how the total lent money is distributed accross different sectors and how much is currently outstanding
### 2. Borrower Risk Assessment
Here I assess the risk associated with different borrowers depending on their Financial Statements, Example - If Net Income is very low compared to amount lent, the borrower is classified as high risk and highlighted on the dashboard
### 3. Covenant Benchmarks
On this tab I track the status of agreed covenants and if borrowers are meeting the required thresholds, months in which thresholds are not met are highlighted, so see if there is a trend or continous months where thresholds were not met
Also, I am showing here what is the headroom i.e. by how much the borrowers differ from the set thresholds (positive or negative). Negative headroom is highlighted.

## Design
The project uses sample input files:
* `Dummy_Borrowers.csv` - contains information about Borrowers
* `Dummy_Financial.csv` - contains financial statements like Balance Sheet, Income Statements of Borrowers
* `Dummy_Covenants.csv` - contains information of agreed loan covenants with their thresholds and status

Some data cleansing and transformations like pivoting are applied to the data in Python using the `Data Cleansing.ipynb` file. Cleaned files are stored in Transformed folder and used in Tableau for Analytics.
