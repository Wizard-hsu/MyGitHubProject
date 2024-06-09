# US Campaign Finance Analytics

## Problem Statement
For many new candidates running for office, analyzing the raw data provided by the Federal Election Commission (FEC) can be an overwhelming and complex task. The vast amount of data, including candidate information, committee details, political action committees (PACs), and financial transactions, requires sophisticated analysis to extract meaningful insights.

## Solution
By analyzing the data files from previous years and generating curated data tables, we can create comprehensive reports that provide a clear understanding of election expenditures. This project aims to transform raw data into actionable insights, helping candidates and stakeholders make informed decisions.

## Data Source
The data for this project is retrieved from the US Campaign Finance Data provided by the Federal Election Commission (FEC).

- **URL**: [US Campaign Finance Data – Federal Election Commission (FEC)](https://www.fec.gov/data/browse-data/?tab=bulk-data)
- **Description**:
  - The dataset is approximately 15 GB in size and contains information on nearly 28 million individuals.
  - It includes data on candidates, committees, political action committees (PACs), House and Senate campaigns, as well as transactions, individual and committee contributions, operations, and independent expenditures for US elections.

## Software Tools and Technologies
The project utilizes the following tools and technologies:
- **Databricks**
- **Spark**
- **Tableau**

## Project Structure
US-Campaign-Finance-Analytics/
├── data/
│ ├── raw/
│ │ └── FEC_data.zip
│ └── processed/
│ └── curated_data.csv
├── notebooks/
│ ├── data_preparation.ipynb
│ ├── data_cleaning.ipynb
│ └── data_analysis.ipynb
├── scripts/
│ ├── data_download.py
│ ├── data_transformation.py
│ └── generate_reports.py
├── dashboards/
│ └── Tableau_Dashboard.twb
