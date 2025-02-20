# GR5243 Project 1:

## Project Overview
This project explores the relationship between **S&P 500 market trends in 2024** and **news articles** using **Yahoo Finance (`yfinance`) & The Guardian API**.  
The goal is to acquire, clean, preprocess, and merge financial data with relevant news articles for further analysis.  
We applied **Data Acquisition, Data Cleaning, Explorative Analysis, Data Preprocessing and Feature Engineering** to designed a robust dataset that allows for further predictive modeling and deeper financial insights.

---
## Requirement
You must run and install packages either in a virtual environment, conda environment, or locally.

Python:
- yfinance == 0.2.54
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- scipy

R: 
  - dply
  - tidytext
  - lubridate
  - stringr
  - vader
  - ggplot2

For **data.py**, you need to get your own api key from [The Guardian](https://bonobo.capi.gutools.co.uk/register/developer) and replace in
- `guardian_api_key = "api_key_here" `

---

## Files
- [data.py](data.py) - Data acquision, data cleaning and merging datasets
- [sp500_df.csv](sp500_df.csv) - raw s&p500 data file
- [news_df.csv](news_df.csv) - raw news article data file
- [merged_df.csv](merged_df.csv).csv -final raw data file
- [EDA.ipynb](EDA.ipynb) - EDA
- [Preprocessing.ipynb](Preprocessing.ipynb) - Data Preprocessing
- [categorical_feature_transform.ipynb](categorical_feature_transform.ipynb) - Categorical Feature Transformation
- [feature engineering.Rmd](<feature engineering.Rmd>) - Feature Engineering
- [final_dataset.csv](final_dataset.csv) - Final dataset

---

## Team Contributions

| Task                        | Contributor       |
|-----------------------------|------------------|
| **Data Acquisition**        | John Feng       |
| **Exploratory Data Analysis** | Sally Liu       |
| **Data Preprocessing**      | Jimin Park       |
| **Feature Engineering**     | Sara Hassani     |

