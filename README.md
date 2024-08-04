# REGRESSION PROJECT - 
## TIME SERIES MACHINE LEARNING - The Case of Corporation Favorita

<a name="readme-top"></a>

<div align="center">
  <br/>

  <h3><b>Time Series Analysis and Favorita Store sales prediction</b></h3>

</div>

#  Table of Contents

- [ Table of Contents](#-table-of-contents)
- [ \[Analyze and Predict Store Sales\] ](#-Analyze-and-Predict-Store-Sales-)
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
| LP3 | Regression Project-The Case of Favorita Stores Sale Prediction | https://medium.com/@oseivictor10/time-series-analysis-the-case-of-corporation-favorita-ea9085d2a388  | https://app.powerbi.com/groups/me/reports/8a247fc4-7d4d-4bc7-a2f8-63dec3b87871/2ab61f7ce3eeb8e3b63a?experience=power-bi |

## Business Scenario
As data scientists in Corporation Favorita, a large Ecuadorian-based grocery retailer, we are tasked to ensure that there is always the right quantity of products in stock.
To do this we have decided to build a series of machine learning models to forecast the demand of products in various locations.We have been provided with some datasets to help in this project.


## Project Description <a name="project-description"></a>
This project aims to ensure optimal inventory levels at Corporation Favorita, by leveraging machine learning models to forecast product demand across various locations. Accurate demand forecasting will help maintain the right quantity of products in stock, reducing instances of overstocking and stockouts, thereby enhancing customer satisfaction and minimizing operational costs. The project follows the CRISP-DM framework and utilizes data provided by the marketing and sales teams to develop and validate predictive models
  

## Objectives of Project <a name="objectives-of-project"></a>
The primary objective of this project is to develop and implement a series of machine learning models to accurately forecast the demand for various products across different locations of Corporation Favorita. By achieving this objective, Corporation Favorita aims to optimize its inventory management, ensuring that the right quantity of products is consistently in stock. 


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
- GitHub: [Victor-Osei]
- LinkedIn: [Victor Osei Duah]