# Web Scraping and Data Analysis of Largest Companies in the United States with Power BI Dashboard

This repository contains Python code for scraping data from a real website and analyzing it using Pandas. Specifically, it scrapes the list of largest companies in the United States by revenue from Wikipedia and performs data analysis on it. Additionally, it includes a Power BI dashboard named "Companies Dashboard" for visualization.

## Requirements

- Python 3.x
- Beautiful Soup 4 (`bs4`)
- Requests
- Pandas
- Power BI Desktop (for viewing and modifying the dashboard)

## Usage

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Python script `scrape_and_analyze.py`:

    ```bash
    python scrape_and_analyze.py
    ```

    This script will scrape the data from [Wikipedia's list of largest companies in the United States](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue), save it as a CSV file (`Companies.csv`), and generate analysis using Pandas.

4. Open the Power BI dashboard `Companies Dashboard.pbix` using Power BI Desktop for visualization and further analysis. You can modify the dashboard layout, add additional visualizations, or connect it to other data sources as needed.

## Directory Structure

- `scrape_and_analyze.py`: Python script for scraping data and performing analysis.
- `Companies.csv`: CSV file containing the scraped data.
- `Companies Dashboard.pbix`: Power BI dashboard for visualizing the data.
![Screenshot 2024-04-22 203847](https://github.com/NigarAliyeva1/Companies-Dashboard/assets/112957859/ad49b8f3-cbef-48d1-acc7-0daf91dc4581)
