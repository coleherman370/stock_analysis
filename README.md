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

- Refactoring the script resulted in large performance increases. 
* The overall run time of the script reduced from an average of .83 seconds to .13 seconds (Figure 4)
* This performance enhancement would have serious impact when run with a larger data set

## Summary
Refactoring this to run efficiently would be crucial for this script to run with a production sized data set. With the example set, the number of ticker was 12. In a production environment, this could be hundreds and even thousands. Without refactoring the script, the run time would be so long it would be frustrating to use for production purposes. There still need to be some improvements made into how the script indentifies unique tickers. If that were done, this script as is could be scaled up to handle hundreds of lines of similar data without having excessive run times.

## Figures

### Figure 1: 
[Script Run Time - Refactored.](https://github.com/coleherman370/stock_analysis/blob/main/Resources/VBA_Challenge_2018.png)

### Figure 2:
[2017 Stock Analysis Results.](https://github.com/coleherman370/stock_analysis/blob/main/Resources/VBA_Challenge_2017_Stock_Analysis.png)

### Figure 3:
[2018 Stock Analysis Results.](https://github.com/coleherman370/stock_analysis/blob/main/Resources/VBA_Challenge_2018_Stock_Analysis.png)

### Figure 4:
[Script Run Time - Pre-refactoring](https://github.com/coleherman370/stock_analysis/blob/main/Resources/green_stocks_2017.png)