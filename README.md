# Stock Analysis using Visual Basic

## Overview of Project
Perform an annual analysis of multiple stock ticker trading history.

## Analysis
An analysis of annual trading volume and returns is performed using a VBA script. Triggered by a button, the macro runs and compiles the daily tracking data of specific stock tickers into an report. This script has approximately a .13 second average run time (Figure 1).This report provides a sum to of the total annual trading volume and the percentage of gain/loss of the opening and closing rates for the year (Figure 2).  

### Challenges
An improvement needed for production use would be comprising a list of tickers based on the data rather than hard coding ticker values. This way the script can be versatile enough to handle randomly added tickers. Another improvement would be to add data prep to the script that organizes the data by ticker and date. The script is currently dependent on the being correctly sorted.

## Results
- The tickers tracked overall performed better in 2017 than in 2018. 
 - The average gain/loss rate in 2017 was 67.3%. In 2018, this rate was -8.5%. 
 - In 2017 there were 4 tickers that netted a gain exceeding 100% returns.

## Figures

### Figure 1: 
[Script Run Time.](https://github.com/coleherman370/stock_analysis/blob/main/Resources/VBA_Challenge_2018.png)

### Figure 2:
[2017 Stock Analysis Results.](https://github.com/coleherman370/stock_analysis/blob/main/Resources/VBA_Challenge_2017_Stock_Analysis.png)

### Figure 3:
[2018 Stock Analysis Results.](https://github.com/coleherman370/stock_analysis/blob/main/Resources/VBA_Challenge_2018_Stock_Analysis.png)