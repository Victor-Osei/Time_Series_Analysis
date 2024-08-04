# REGRESSION PROJECT - 
## TIME SERIES MACHINE LEARNING - The Case of Corporation Favorita

<a name="readme-top"></a>

<div align="center">
  <br/>

  <h3><b>"Forecasting Sales in Retail: A Machine Learning Approach for Corporation Favorita"</b></h3>

</div>

#  Table of Contents

- [ Table of Contents](#-table-of-contents)
- [ \["Forecasting Sales in Retail: A Machine Learning Approach for Corporation Favorita"\] ](# Forecasting Sales in Retail: A Machine Learning Approach for Corporation Favorita )
    - [Summary ](#summary-)
    - [ Project Description ](#-project-Description-)
    - [Objectives of Project](#-objective-of-Project-)
    - [Goal of Project](#-goal-of-Project-)
    - [ Data ](#-data-)
    - [ Hypothesis ](#-hypothesis-)
        - [ Conclusion on hypothesis](#-conclusion-on-hypothesis-)
    - [ Research Questions ](#-research-Questions-)
    - [ Installation ](#-installation-)
    - [ Author ](#-author-)
    - [ License ](#-license-)


## Summary <a name="summary"></a>
| Code      | Name        | Published Article |  Deployed Power BI |
|-----------|-------------|:-------------:|------:|
| LP3 | Regression Project-The Case of Favorita Stores Sale Prediction | '[Published Article](https://medium.com/@akuaakonnor43/time-series-machine-learning-the-case-of-corporation-favorita-65a96b138f1b)'  | [Power Bi File](https://app.powerbi.com/links/9v5MW2poe2?ctid=4487b52f-f118-4830-b49d-3c298cb71075&pbi_source=linkShare) |

## Business Scenario
As data scientists in Corporation Favorita, a large Ecuadorian-based grocery retailer, we are tasked to ensure that there is always the right quantity of products in stock.
To do this we have decided to build a series of machine learning models to forecast the sales of products in various locations.We have been provided with some datasets to help in this project.


## Project Description <a name="project-description"></a>
This project develops a machine learning model to predict sales at Favorita stores by analyzing trends, customer behavior, and external factors like holidays and promotions.
Our insights will enable our client to optimize inventory, refine marketing strategies, and enhance profitability. We’ve created both statistical and machine learning models to ensure accuracy and flexibility.
  

## Objectives of Project <a name="objectives-of-project"></a>
The primary goal was to design and deploy machine learning models that accurately predict sales across various Corporation Favorita locations, enabling the company to optimize inventory management and enhance profitability


## Goal of Project <a name="goal-of-project"></a>
Build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores

## Data <a name="data"></a>
The datasets where extracted from three(3) places. 

* First dataset - Three (3) tables(oil prices, holiday events, and stores) were extracted from Microsoft SQL Server
* Second dataset - Two (2) tables(sample_submission, and test) were downloaded from OneDrive
* Third dataset - Two(2) tables (train and transactions) were downloaded from a GitHub Repository

## Hypothesis <a name="hypothesis"></a>
* H_o: Promotional activities have no significant effect on product sales.
* H_a: Promotional activities positively impact product sales, leading to increased sales during promotional periods

### Conclusion on hypothesis <a name="conclusion-on-hypothesis"></a>
We reject the null hypothesis and conclude that promotions has significant effect on sales

## Research Questions <a name="research-questions"></a>
1. Is the train dataset complete (has all the required dates)?
2. Which dates have the lowest and highest sales for each year (excluding days the store was closed)?
3. Compare the sales for each month across the years and determine which month of which year had the highest sales.
4. Did the earthquake impact sales?
5. Are certain stores or groups of stores selling more products? (Cluster, city, state, type)
6. Are sales affected by promotions, oil prices and holidays?
7. What analysis can we get from the date and its extractable features?
8. Which product family and stores did the promotions affect.
9. What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them?)
10. Does the payment of wages in the public sector on the 15th and last days of the month influence the store sales.

## Installation: <a name="installation:"></a>
* pyodbc  
* python-dotenv
* openpyxl
* missingno
* scikit-learn
* pmdarima
* statsmodels

## Author <a name="author"></a>
Team Fiji
- Github: [Team Fiji- Github Repo](https://github.com/Victor-Osei/Time_Series_Analysis)