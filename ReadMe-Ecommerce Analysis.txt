Brazil E-commerce Dataset Analysis

Overview

This repository contains data cleaning scripts and Power BI dashboards for analyzing the Olist dataset. The Olist dataset is a well-known Brazilian e-commerce dataset that includes information about orders, customers, products, payments, and reviews from multiple products.

Repository Contents

1. SQL for Data Cleaning 

Description: SQL was used to clean and preprocesses the raw Olist dataset to make it suitable for analysis. It includes steps such as handling missing values, normalizing data formats, and creating aggregated tables for improved dashboard performance.

2. Power BI Dashboards

I have used power bi to create my dashboard, it has 4 main pages: A brief overview of dataset, Customer, Review, Delivery. Along with that I have tried to forecast orders using Poweri bi itself, post that i have used LR and LSTM-RNN for prediction. 

These Power BI dashboards provide visual insights into key business metrics, including:

Sales trends over time

Customer behavior analysis

Payment method distributions

Review scores and customer satisfaction


3. Forecasting.

I divided my data into a 80:20 ratio and trained the model. I used 2 training models Linear Regression and a Neural Network- LSTM-RNN to compare the accuracy and I found out that LSTM-RNN had better accuracy with MSE of around 0.002 as compared to 0.01 for Linear Regression. 

How to Use

Run the SQL Script: Execute Olist_datacleaning.sql in a database environment to clean and prepare the dataset.

Load Data into Power BI: Use the cleaned dataset to create meaningful reports and insights.

Explore the Dashboards: Review the included Power BI PDF reports for insights and trends.

Forecasting: I used python for running the script. 


