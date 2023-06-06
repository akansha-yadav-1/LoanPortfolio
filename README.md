# Loan Portfolio Management Analytics

## Overview
This project focuses on the development of a Loan Portfolio Management Dashboard for tracking the lending activities of a bank. The dashboard provides insights into the distribution of lent amounts across different sectors and monitors outstanding balances. It also includes risk assessment of borrowers based on their financial statements and tracks covenant benchmarks to ensure compliance.

## Dashboard Tabs
The Loan Portfolio Management Dashboard consists of three main tabs:

### 1. Loan Portfolio Overview
This tab presents an overview of the total lent amount and its distribution across various sectors. It provides a snapshot of the outstanding balances in the loan portfolio.

### 2. Borrower Risk Assessment
In this tab, the risk associated with different borrowers is assessed based on their financial statements. For example, borrowers with significantly low net income compared to the amount lent are classified as high risk. The high-risk borrowers are highlighted on the dashboard for easy identification.

### 3. Covenant Benchmarks
The Covenant Benchmarks tab tracks the status of agreed loan covenants and monitors whether borrowers are meeting the required thresholds. Months in which the thresholds are not met are highlighted, allowing users to identify trends or continuous periods of non-compliance. Additionally, the tab displays the headroom, indicating the deviation of borrowers from the set thresholds (positive or negative). Negative headroom values are highlighted for quick identification.

## Design
The project utilizes the following sample input files:

- `Dummy_Borrowers.csv`: Contains borrower information
- `Dummy_Financial.csv`: Includes financial statements such as balance sheets and income statements of borrowers
- `Dummy_Covenants.csv`: Provides details of agreed loan covenants, their thresholds, and status

Python is used for data cleansing and transformation tasks, which involve applying operations such as data pivoting. These processes are implemented in the `Data Cleansing.ipynb` file. The cleaned files are then stored in the Transformed folder and utilized in Tableau for generating insightful analytics.

Please note that this is a brief overview of the project. Further details regarding specific analytics and functionalities can be explored within the dashboard itself.

### View the dashboard [here](https://public.tableau.com/views/LoanPortfolioManagement/LoanPortfolioOverview?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link_)
