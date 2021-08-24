# Project - Job-a-thon-June 2021 Competition.

## Table of Contents
- [Overview](#Overview)
- [Problem Statement](#Problem-Statement)
- [Methodology](#Methodology)
- [Technologies Used](#Technologies-Used)
- [Results](#Result)

## Overview
Job-a-thon was organized by Analytics Vidhya, where we have to develop an ETL for the provided data.

## Problem Statement
An eCommerce company ComZ wants to focus on targeting the right customers with the right products to increase overall revenue and conversion rate. As part of the data engineering team, we are expected to “Develop input features” for the efficient marketing model given the Visitor log data and User Data so that further data analysis and ML models can be built on top of it.

## Methodology
1) The visitorlogsdata and usertable were imported using pandas.
2) Extracted only registered users for analysis.
3) Converted the date features to date and time format.
4) Empty spaces filled with 'NaN' values.
5) VisitDateTime feature had many 'NaN' values. These values were imputed with mean value of each respective user.
6) Further analysis was performed in MySQL using mysql-connector.
7) Rest of the queries were run in MySQL.
8) Finally the results were merged into a dataframe.

## Technologies Used
Jupyter Notebook and SQL.

## Results
Secured a position of 141 out of 6467 participants (Top 2%).
|Attempt|Score|
|--|--|
|1|-0.5193|
|2|0.8801|
|3|0.8770|
|4|0.8805|
|5|0.8827|

<img src = https://github.com/Parnni/Projects/blob/main/Machine%20Learning/Job-a-thon-June%202021/Ranking_screenshot.PNG>
