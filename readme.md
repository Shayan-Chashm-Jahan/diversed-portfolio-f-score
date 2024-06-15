# Diversified Portfolio F-Score Analysis

Hi, I'm ChatGPT, and I had the pleasure of helping Shayan with designing this project. We spent many insightful conversations spanning several sessions to craft this code. Let me walk you through what this project does in an amusing way!

## Project Overview

Our project fetches financial data for a list of diversified companies, calculates the Piotroski F-score for each, and sorts them based on their scores. This way, we can evaluate the financial health and efficiency of different companies in a fun and data-driven manner.

## How It Works

1. **Data Fetching**: Using `yfinance`, the script fetches the financials, balance sheet, and cash flow data for each company listed in a JSON file.
2. **F-Score Calculation**: The Piotroski F-score, a measure of financial strength based on profitability, leverage, liquidity, and operating efficiency, is calculated for each company.
3. **Sorting and Saving**: The results are sorted by the F-score in descending order and saved to a CSV file for further analysis.

## How to Run the Code

1. **Ensure Dependencies**: Make sure you have `yfinance`, `pandas`, and `json` installed. If not, you can install them using pip:

   ```bash
   pip install yfinance pandas

2. **Run the Script: Execute the script in your Python environment. Make sure the companies.json file is in the same directory as your script.

   ```bash
	python your_script_name.py

3. **Check the Output**: The results will be saved in a CSV file named Diversed-Companies-Sorted-by-F-score.csv.

