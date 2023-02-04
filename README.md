# Financial Risk Factors AI Estimator
Multivariate regression for financial risk estimation

### PROJECT GOAL <br>
Estimating a regression of Apple returns on an alpha plus exposures to four risk factors (MkT_RF, SMB, HML, Mom) at a monthly frequency.

### METHODOLOGY <br>
Supervised Learning

### PROBLEM TYPE <br>
Financial Analysis

### STEP-BY-STEP OUTLINE <br>
I. Using the Kenneth French library to extract both the three factor model data and the momentum risk factor data. 
Use Yahoo Finance to extract the monthly returns of a risk asset of your choice (in this case we picked Apple).

II. Pre-process the data to obtain a dataframe that combines the three data sources.

III. Perform our regression on the merged dataframe and interpret the results.

### DATA SOURCES <br>

FamaFrench data library

https://pandas-datareader.readthedocs.io/en/latest/readers/famafrench.html

Yahoo Finance

https://pypi.org/project/yfinance/

### TECHNOLOGIES USED <br>
IDE: Google Colaboratory

Language used: Python

Libraries: Pandas, Matplotlib, Statsmodels
