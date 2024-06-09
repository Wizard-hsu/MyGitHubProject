# US Campaign Finance Analytics

## Problem Statement
For analysis of expenditure for contesting in an election, most of the new candidates cannot analyze the raw data provided by the FEC (Federal Election Commission).

## Solution
By analyzing the data files of previous years and generating curated data tables which will indeed create reports that describe overall understandings of expenditures.

## Data Source
Retrieved from:
[US Campaign Finance Data – Federal Election Commission(FEC)](https://www.fec.gov/data/browse-data/?tab=bulk-data)

- **Description**:
  - The dataset is approximately 15 GB in size and contains information on nearly 28 million individuals.
  - It includes data on candidates, committees, political action committees (PACs), House and Senate campaigns, as well as transactions, individual and committee contributions, operations, and independent expenditures for US elections.

## Software Tools and Technologies
- Databricks
- Spark
- Tableau

 ## Importing Data

### Importing Data Files (.txt) and .csv Files into Databricks
- The first step in the data processing pipeline is to import data files from various sources into Databricks.
- Data files include both .txt files and .csv files.
- We will read all the files and proceed with further processing.

### Reading Data Files
- For files without headers, we will create a custom schema to ensure proper data structure.
- CSV files with headers will be read directly using their predefined structure.

## Data Cleaning

### Converting File Types and Loading
- Once the data files are imported, we will convert them into appropriate file types for processing.
- Data will be loaded into Databricks for further analysis.

### Checking for Nulls and Dropping Them
- Null values can affect the accuracy of analysis, so we will check for and handle any null values appropriately.
- Null values will be dropped from the dataset to ensure data integrity.

## List of Files After Loading
- After the data cleaning process, we will provide a list of all the files that have been successfully loaded into Databricks.

## Data Visualizations

### Visualization for Total Receipts for Each Candidate
- Total Receipts represent anything of value received by a political committee. This visualization will provide an overview of the financial support received by each candidate.

### Transaction Amount in Each State
- This visualization will display the transaction amount in each state, giving insights into where the campaign spending is concentrated geographically.

### Total Disbursements by Candidates
- Disbursements cover both expenditure and other types of payments not made to influence federal elections. This visualization will illustrate the total disbursements made by each candidate, providing insights into their spending patterns.

### Transaction Amount for Each Contesting Candidate
- This visualization will show the transaction amount for each candidate contesting in the election, allowing for comparisons between candidates.

### Total Individual Contributions Made by Candidates
- Individual contributions play a significant role in campaign finance. This visualization will depict the total individual contributions made to each candidate, highlighting their level of grassroots support.

### Visualization of COH_BOP and COH_COP for Each Party
- Cash on Hand at the Beginning of Period (COH_BOP) and Cash on Hand at the Close of Period (COH_COP) are crucial indicators of a committee's financial health. This visualization will compare COH_BOP and COH_COP for each party, providing insights into their financial positions.

### Visualization for Transfers from Authorized Committees to the Candidates
- This visualization will depict the transfers from authorized committees to the candidates. It will illustrate the flow of funds between committees, indicating the level of support candidates receive from party organizations and other committees.

### Summary
The Campaign Finance Analytics project empowers candidates, committees, and stakeholders with actionable insights to navigate the complex landscape of election finance, ultimately contributing to fair and transparent democratic processes.

### Visualization of Transaction Amount by State for Campaigning
- This visualization will show the transaction amount by state for campaigning purposes. It will provide insights into the distribution of campaign expenditures across different states.

By visualizing these key aspects of campaign finance data, stakeholders can gain a deeper understanding of financial trends, contributions, and spending patterns in political campaigns. These insights can inform strategic decisions and resource allocation during election campaigns.
