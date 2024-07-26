# Uber Price Prediction Project

## Author: Abel Tekle

## Project Overview

This project aims to develop a model to predict the price of Uber rides in New York City. Using a dataset of 200,000 Uber rides from 2009 to 2015, the project explores various factors influencing ride prices and builds predictive models.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Source](#data-source)
3. [Installation](#installation)
4. [Data Inspection](#data-inspection)
5. [Data Cleaning](#data-cleaning)
6. [Feature Engineering](#feature-engineering)
7. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
8. [Model Preparation](#model-preparation)
9. [Model Fitting and Tuning](#model-fitting-and-tuning)
10. [Results and Evaluation](#results-and-evaluation)
11. [Conclusion](#conclusion)
12. [Contributing](#contributing)
13. [License](#license)

## Introduction

Uber is a ride-sharing platform that connects passengers with drivers through a mobile app. The aim of this project is to analyze the factors affecting Uber ride prices and create models to predict these prices accurately.

## Data Source

The dataset used in this project is obtained from Kaggle: [Uber Fares Dataset](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset/data).

## Installation

To run this project, dowload Main.rmd file  you need to have R installed on your machine. Additionally, the following R packages are required:

- `corrplot`
- `discrim`
- `corrr`
- `MASS`
- `tidyverse`
- `tidymodels`
- `ggplot2`
- `dplyr`
- `geosphere`
- `ranger`
- `xgboost`
- `dials`
- `tune`
- `reader`
- `knitr`
- `kableExtra`
- `tidytext`
- `vembedr`

You can install these packages using the following commands:

```r
install.packages(c("corrplot", "discrim", "corrr", "MASS", "tidyverse", "tidymodels", "ggplot2", "dplyr", "geosphere", "ranger", "xgboost", "dials", "tune", "reader", "knitr", "kableExtra", "tidytext", "vembedr"))
```


##Data Inspection

Before applying any machine learning techniques, we need to inspect the dataset and modify it as needed. The initial inspection involves reading the data and understanding its structure.

##Data Cleaning

Data cleaning involves removing unnecessary columns, handling missing values, and correcting errors in the dataset.

##Feature Engineering

Feature engineering includes adding new features to enhance the dataset's predictive power, such as extracting date and time components and calculating distances.

##Exploratory Data Analysis (EDA)

EDA involves analyzing the distribution and relationships between variables to gain insights into the dataset.

##Model Preparation

Model preparation includes splitting the data into training and testing sets and creating a recipe for the models. The recipe involves normalizing numeric predictors and one-hot encoding categorical variables.

##Model Fitting and Tuning

Various models are fitted and tuned to find the best performing model. The models used in this project include:

Linear Regression
Ridge Regression
Lasso Regression
Polynomial Regression
K Nearest Neighbors
Elastic Net
Random Forest
Boosted Trees
Results and Evaluation

The performance of each model is evaluated using Root Mean Squared Error (RMSE). The best model is selected based on the lowest RMSE.

##Conclusion

The project concludes with insights drawn from the analysis and the performance of the models. Suggestions for future research and potential improvements are also provided.

##Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request.

##License

This project is licensed under the MIT License - see the LICENSE file for details.
