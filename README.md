
# Web Scraping Project: Largest U.S. Companies by Revenue

## Overview

This project extracts structured financial and corporate data from Wikipedia’s “List of Largest Companies in the United States by Revenue” page using Python.

The scraped data is transformed into a structured Pandas DataFrame suitable for analysis and export.

The project demonstrates practical application of web scraping, data cleaning, and dataset preparation.



## Project Objective

To:

- Extract company ranking data from the first Wikipedia table
- Structure the data into a Pandas DataFrame
- Clean numeric fields for analysis
- Export the dataset for further use



## Data Extracted

The following fields were collected:

- Rank  
- Company  
- Industry  
- Revenue (USD Billions)  
- Employees  
- Headquarters  



## Technologies Used

- Python 3  
- requests  
- BeautifulSoup  
- pandas  



## Methodology

1. Send HTTP request with a custom User-Agent.
2. Parse webpage using BeautifulSoup.
3. Locate the first relevant data table.
4. Extract row data (tr → td).
5. Store extracted data in a list.
6. Convert the list into a Pandas DataFrame.
7. Clean numeric columns.
8. Export dataset to CSV.


## How to Run

1. Install dependencies:

pip install requests beautifulsoup4 pandas

2. Open the notebook:

jupyter notebook

3. Run all cells sequentially.



## Output

- Structured Pandas DataFrame  
- Cleaned dataset ready for analysis  
- Optional CSV export file  


## Potential Extensions

- Revenue trend analysis  
- Industry comparison  
- Data visualization  
- Automation for periodic updates  



