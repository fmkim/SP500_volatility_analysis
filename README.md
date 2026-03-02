# SP500_volatility_analysis
A Python-based analysis of S&amp;P 500 stock data to identify and visualize market volatility
Project Overview
This project analyzes historical S&P 500 stock market data to identify significant market movements and volatility trends. 
Originally developed as a technical skill drill, the tool processes time-series data to pinpoint the day with the greatest 
absolute price fluctuation and visualizes long-term performance trends.

Key Features:

Volatility Detection: Custom logic to calculate daily percent change and identify outliers in market behavior.

Data Visualization: Interactive charts showing the S&P 500 closing prices over time using Matplotlib.

Environment Management: Built and managed within a dedicated Anaconda virtual environment to ensure reproducibility.

Live Data Integration:Integrated yfinance API to allow for real-time data fetching beyond the static CSV.

Tech Stack

Language: Python 3.9

Environment: Anaconda / JupyterLab

Libraries: Pandas, Matplotlib, yfinance, csv, os

Version Control: Git / GitHub

Methodology

Data Extraction: Imported S&P 500 data from Yahoo Finance via CSV and API.Processing: 
Iterated through datasets using csv.DictReader to calculate:$$\text{Percent Change} = \frac{\text{Close} - \text{Open}}{\text{Open}} \times 100$$

Analysis: Used absolute value comparisons to find the "Maximum Volatility" day, ignoring the direction of the swing to focus on total movement.

Visualization: Plotted historical trends to correlate volatility spikes with major global economic events.

Setup & Installation

To run this project locally, ensure you have Anaconda installed, then:

Clone the repository 

Install dependencies

Launch JupyterLab
