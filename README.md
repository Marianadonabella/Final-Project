![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Final Project | DA Bootcamp


## Introduction

This repository contains the final project of the Data Analytics bootcamp, at Ironhack Barcelona (March,2021).

## The Project

The project consists of predicting staff turnover of a company. 
A rise in staff attrition will be costly to companies, and combining these predictions with employee performance and potencial, makes it possible for companies to focus on the right people to perform retention initiatives.
The goal was to build a model using the most common variables, the kind of information the majority of companies already have.
The metrics used to evaluate the quality of the predictions was accuracy.

## Data

There are two different analysis in the project: the machine learning model, and the analysis of overall staff turnover in the US.

- Machine Learning Model:

The data used can be found on Kaggle. It contains 15.000 observations, each one representing an employee, and 9 variables: 

1.Satisfaction Level
2.Last Evaluation 
3.Number Projects 
4.AVG Monthly Hours
5.Time in Company
6.Work Accident
7.Promotion Last 5 years
8.Salary
9.Department
10.Left company

- US employee turnover analysis:

The data is provided by the Bureau of Labor Statistics, through an yearly survey called Job Openings and Labor Turnover Survey (JOLTS).
The sample consists in aproximately 16.000 business establishments in the US, contemplating every industry and every State.
In this project, multiple datasets from JOLTS were used.
More information on the data can be found here: https://www.bls.gov/jlt/



## Workflow

The general workflow can be splitted into 5 main steps:

First step: deciding topic and exploring information
Second step: gathering datasets
Third step: cleaning data (dealing with missing values, checking correlations, outliers...)
Fourth step: performing machine learning strategies and checking for the quality of each model
Fifth step: refining data visualization

## Content

In this repository you'll find:
- Folder "data": data used for bulding the model, JOLTS data about general US quiting numbers, JOLTS data about general US current employees numbers
- Folder "analysis": eploration of different datasets, final notebook with ML prediction
