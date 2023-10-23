# OilCompany
Bootstrap and ml
## Table of contents
* [General info](#general-info)
* [Features](#features)
* [Process](#process)
* [Stack](#stack)
* [Conclusion](#conclusion)

## General info
This project aims to pick the best region with the least amount of loss probabilty
## Features
* id — id of oil rig
* f0, f1, f2 — just three features;
* product — oil in the rig
## Process
|Stage | Description|
|--------|--------|
|First stage| Data preprocessing: removing Nans and giving data a good (and right) look|
|Second stage|Model training and predicting the amount of oil |
|Third stage| All calculations needed for finding the most profitable rigs|
|Fourth stage| Bootstrap and confidence intervals|
## Stack
Project is created with:

* Pandas
* Sklearn
  1. Model_selection.train_test_split
  3. sklearn.metrics.mean_squared_error
  4. sklearn.linear_model.LinearRegression
* Numpy
* pandas_profiling
	
## Conclusion
* Calculated the best region(biggest profit) with the least amount of risk(p-value)


