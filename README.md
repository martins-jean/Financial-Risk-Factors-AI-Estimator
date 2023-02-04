# Financial Risk Factors AI Estimator
Multivariate regression for financial risk estimation

PROJECT GOAL
Estimating a regression of Apple returns on an alpha plus exposures to four risk factors (MkT_RF, SMB, HML, Mom) at a monthly frequency.

METHODOLOGY
Supervised Learning

PROBLEM TYPE
Financial Analysis

STEP-BY-STEP OUTLINE
I. Using the Kenneth French library to extract both the three factor model data and the momentum risk factor data. 
Use Yahoo Finance to extract the monthly returns of a risk asset of your choice (in this case we picked Apple).

II. Pre-process the data to obtain a dataframe that combines the three data sources.

III. Perform our regression on the merged dataframe and interpret the results.

DATA SOURCES

FamaFrench data library

https://pandas-datareader.readthedocs.io/en/latest/readers/famafrench.html

Yahoo Finance

https://pypi.org/project/yfinance/

TECHNOLOGIES USED
IDE: Google Colaboratory

Language used: Python

Libraries: Pandas, Matplotlib, Statsmodels
