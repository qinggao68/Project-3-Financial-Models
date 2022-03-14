# Project-3-Financial-Models

# Purpose

The purpose of this project is to perform portfolio analysis in python. The stocks in my portfolio are: Target, Chevron, General Electric, Teladoc Health, NextEra Energy, American Express, Coca-Cola, and Phillips 66. I also benchmarked my portfolio to iShares Core S&P 500 ETF(IVV) as it contained all the stocks I have selected except Teladoc Health. 

There are four major parts to my analysis: 
1. randomly assigned portfolio weights to calculate some common metrics like sharpe ratio 
2. utilized the fama-french 5 factors model and compare that to my portfolio 
3. ran a monte carlo simulation and utilized the scipy package to determine the optimal portfolio weights under the condition of achieving maximum sharpe ratio or minimal volatility 
4. created a tear sheet 

Please view the project scope section for a more detailed outline of the analysis. 

## Additional Information

I tried to make my code as much as automated, meaning that if you are interested in finding the optimal weights of your own selected stocks, all you have to do is just change the ticker(s). The only data that need to be updated is the fama-french 5 factors, but this can easily accessed online(please see the link to download the updated data). 

NOTE: quantstats package provide a html file to access the tear sheet, so you would need to run on your computer to view the tear sheet. 

# Project Scope(steps?) 
1. Data Exploration 
2. Percentage Changes & Standard Deviation 
3. Skewness & Kurtosis 
4. Sortino Ratio 
5. Fama-French 5 Factor Model 
6. Monte Carlo Simulation 
7. Scipy Package to Optimize Portfolio Weights 
8. Tear Sheet

## References 
[Fama-French 5 Factors Model data] https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html

[QuantInsti Blog] https://blog.quantinsti.com/portfolio-optimization-maximum-return-risk-ratio-python/

[quantstats documentation] https://github.com/ranaroussi/quantstats
