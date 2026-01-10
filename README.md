# Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard

# Stock and Revenue Data Analysis Project

## Table of Contents

1. **[Project Overview](#project-overview)**  
2. **[Technologies Used](#technologies-used)**  
3. **[Define a Function that Makes a Graph](#define-a-function-that-makes-a-graph)**  
4. **[Question 1: Use yfinance to Extract Tesla (TSLA) Stock Data](#question-1-use-yfinance-to-extract-tesla-tsla-stock-data)**  
5. **[Question 2: Use Webscraping to Extract Tesla Revenue Data](#question-2-use-webscraping-to-extract-tesla-revenue-data)**  
6. **[Question 3: Use yfinance to Extract GameStop (GME) Stock Data](#question-3-use-yfinance-to-extract-gamestop-gme-stock-data)**  
7. **[Question 4: Use Webscraping to Extract GameStop Revenue Data](#question-4-use-webscraping-to-extract-gamestop-revenue-data)**  
8. **[Question 5: Plot Tesla Stock and Revenue Graph](#question-5-plot-tesla-stock-and-revenue-graph)**  
9. **[Question 6: Plot GameStop Stock and Revenue Graph](#question-6-plot-gamestop-stock-and-revenue-graph)**  
10. **[Project Structure](#project-structure)**  
11. **[Installation](#installation)**  
12. **[Usage](#usage)**  
13. **[License](#license)**  

---

## Project Overview

This project demonstrates the extraction of historical stock price data using the `yfinance` library and quarterly revenue data through web scraping with `requests` and `BeautifulSoup`. The collected data for **Tesla (TSLA)** and **GameStop (GME)** is then visualized using custom plotting functions built with `matplotlib`.

The project follows the structure of the IBM Developer Skills Network Python for Data Science, AI & Development course final project.

## Technologies Used

- Python 3.x
- pandas
- yfinance
- requests
- beautifulsoup4
- matplotlib

## Define a Function that Makes a Graph

A reusable function is created to plot stock price data (e.g., historical closing prices) alongside revenue data on a dual-axis chart.

## Question 1: Use yfinance to Extract Tesla (TSLA) Stock Data

Tesla stock price history is downloaded using the `yfinance` library for a specified period.

## Question 2: Use Webscraping to Extract Tesla Revenue Data

Quarterly revenue data for Tesla is extracted from a public HTML table using web scraping techniques.

## Question 3: Use yfinance to Extract GameStop (GME) Stock Data

GameStop stock price history is retrieved using the `yfinance` library.

## Question 4: Use Webscraping to Extract GameStop Revenue Data

Quarterly revenue figures for GameStop are scraped from a designated webpage.

## Question 5: Plot Tesla Stock Graph

Tesla's historical stock prices and revenue are visualized together on a combined chart using the defined plotting function.

## Question 6: Plot GameStop Stock Graph

GameStop's historical stock prices and revenue data are plotted on a dual-axis graph for comparative analysis.

## Project Structure
