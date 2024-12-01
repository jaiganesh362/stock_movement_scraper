# Stock Movement Prediction 

This project aims to predict stock price movements by scraping data from stock-related discussions and news platforms using ntscraper, 
performing sentiment analysis, and applying machine learning models.

# Setup Instructions

# 1. Prerequisites
Ensure the following are installed on your system:

Python 3.7 or later

pip (Python package manager)

A compatible web browser (e.g., Google Chrome)

# 2. Clone the Repository
Download or clone the project repository containing the Jupyter Notebook and all necessary files:

bash

git clone <https://github.com/jaiganesh362/stock_movement_scraper.git>

cd stock_movement_scraper

# 3. Install Dependencies
Install the required libraries by running the following command:

open requirements.txt file to install the libraries

# 4. Configure WebDriver for Selenium
Download the WebDriver compatible with your web browser:

ChromeDriver

GeckoDriver for Firefox

Place the downloaded WebDriver in your system's PATH or specify its location in the code.

# 5. Running the Jupyter Notebook
Open a terminal or command prompt in the project directory.

Open the stock_predicting_model.ipynb file from the Jupyter interface.

Run all cells sequentially to:

   -Scrape data using ntscraper.
   
   -rocess and clean the scraped data.
   
   -Perform sentiment analysis and feature extraction.
  
   -Train and evaluate a stock movement prediction model.

# 6. Expected Outputs
Scraped Data: Saved as tweets.csv in the project directory

Visualizations: Graphs and charts will be displayed within the notebook.

# Project Structure
stock_predicting_model.ipynb: Main notebook for scraping, analysis, and prediction.

requirements.txt: List of dependencies.

README.md: Instructions and setup details.




