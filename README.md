# Stock-Price-and-Revenue-Analysis-of-Tesla-and-GameStop-2010-2021-
This project was completed as part of the IBM Data Science Professional Certificate (Python Project for Data Science). It involves web scraping, data cleaning, and visualization using Pandas and Plotly


# Tesla and GameStop Stock Analysis

This project analyzes Tesla and GameStop stock data using Python. It involves **web scraping**, **data cleaning**, and **data visualization** to explore historical trends. The work was completed as part of the **IBM Data Science Professional Certificate** (Python Project for Data Science).

## Project Overview

The goal of this project is to:

* Collect stock data using the **yfinance API**.
* Scrape historical revenue data from web sources.
* Clean and preprocess data for analysis.
* Visualize stock trends using **Plotly** for interactive charts.

The analysis covers stock data up to **2021**.

## Tools and Libraries Used

* **Python 3**
* **Pandas** → data manipulation & cleaning
* **yfinance** → fetching stock data
* **Requests** → retrieving web content
* **BeautifulSoup (bs4)** → web scraping revenue data
* **Plotly** → interactive data visualization

## Key Steps

1. **Data Collection**

   * Used `yfinance` to download Tesla and GameStop stock data.
   * Scraped revenue data from online tables using `requests` and `BeautifulSoup` or  `pandas.read_html()`.

2. **Data Cleaning**

   * Removed missing values.
   * Cleaned numeric columns by stripping out `$` and `,` symbols.
   * Converted revenue values into proper numeric format.

3. **Data Visualization**

   * Created interactive line charts with Plotly.
   * Displayed stock price and revenue trends side by side.
   * Limited analysis to data available up to June 2021.

## Example Graph

The final visualization shows Tesla and GameStop stock price trends alongside revenue data.

### Tesla Stock and Revenue  
![Tesla Graph](images/GameStop Stock.png)  

### GameStop Stock and Revenue  
![GameStop Graph](images/gme_stock.png) 

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Hydrosamueldc/Stock-Price-and-Revenue-Analysis-of-Tesla-and-GameStop-2010-2021-.git

   ```
2. Install the required libraries:

   ```bash
   pip install pandas yfinance requests beautifulsoup4 plotly
   ```
3. Open the Jupyter Notebook and run the cells:

   ```bash
   jupyter notebook
   ```

## Project Context

This project is an **end-of-course project** from the **IBM Data Science Professional Certificate (Python Project for Data Science)**.
It demonstrates skills in **Python programming, web scraping, data cleaning, and visualization**.

---

