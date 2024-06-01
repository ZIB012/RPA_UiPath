# Stock Price Trend Comparison

### Background
An automatic stock price trend comparison for an organization is built. Every day, the organization wants to record the rise and fall in the stock prices of two companies called "Exxon RPA Corp." and "WEX Academy Inc." and compare the prices of both companies using a graph. 

### Problem Statement

Build a project in UiPath Studio that extracts the share prices from a website, following a fixed time interval. Create a graphical representation of the data in an excel file. 
- Open [www.rpachallenge.com](www.rpachallenge.com) and navigate to the [RPA Stock Market webpage](https://www.rpachallenge.com/assets/rpaStockMarket/index.html).

- Extract the share prices of the two companies at evere time step and then save them in the [Data.xlsx](Data.xlsx) Excel file.

- Create a double line graph of the collected data to show the changes in the share prices over time in the same excel sheet. 

### Environment Prerequisites

You must ensure that your system environment is equipped with the prerequisites necessary to create and execute the project successfully.

1. System Applications/Software 

   - UiPath Studio: create automation using available project activities

   - Microsoft Excel: store data and create reports

   - Browser (Microsoft Edge / Google Chrome): Extract share prices data from a website

2. UiPath Studio Packages

    - UiPath.Excel.Activities

    - UiPath.System.Activities

    - UiPath.UiAutomation.Activities