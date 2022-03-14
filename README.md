# Purpose

The purpose of this project is to build a various of different financial models using python. I built a Comparable Companies model, a DCF model, and a simple LBO model as in demonstration. 

Note: By no means are these models shown in here are to replaced the financial models you can build in excel. It is merely a supplemental tool that I hope will help speed up the initial valuation process, especially if your team has a couple of interested targets in the pipeline. 

## Comparable Companies Analysis Model

In this notebook, I used FinancialModelingPrep's API to retrieve a various of financial and valuation metrics for UHS, CVS, ANTM, CI, HUM, CNC, and MOH in the healthcare insurance space. Since, I am using a free API that is quite unstable, I am not able to retrieve all the valuation metrics for the selected companies at one time. The best way to do this, if you are also using a free API, is to comment all the other metrics, only retrieve the first metric, run it and write it to xlsx file, then repeat until you have all the valuation metrics you need for your comparable companies analysis model. 

## Discounted Cash Flow Model 

The assumptions and the Income Statement I used are based on one of the deals I was working on in the past. This is a very simple DCF model I built using python. This model can be used as pre-valuation stage as to figure out quickly what the target company is worth. I also built a monte carlo simulation that run 1000 interations to calculate the DCF value. 

## LBO Model

This model is adapted from one of the case studies provided by BreakingIntoWallStreet. It is an hour long CS. The assumptions in my model are based on the instructions provided in the CS. 

## Future Work 

As of now, these models are all standalone. In the future, I hope to create a more complicated DCF model and incorporated the median from the comparable companies analysis model to calculate the terminal value via multiples method. 

## References 
[ADVANCED FINANCIAL MODELING WITH PYTHON] https://nickderobertis.github.io/fin-model-course/lectures/12-free-cash-flow-estimation-and-forecasting.html
