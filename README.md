# Titanic Survival Prediction using Linear Regression

This project aims to predict the survival probability of passengers aboard the Titanic using a linear regression model. The dataset used in this project is a cleaned version of the famous Titanic dataset, which includes various features about the passengers such as class, age, fare, and whether they survived.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [How to Run](#how-to-run)

## Overview
The primary objective of this project is to create a linear regression model that predicts whether a passenger survived the Titanic disaster based on their demographic and ticket-related information. Linear regression is applied here to illustrate how different features influence survival probability.

## Dataset
The dataset contains the following features:
- **pclass**: Passenger's class (1st, 2nd, or 3rd)
- **sex**: Gender of the passenger (Male/Female)
- **age**: Age of the passenger
- **sibsp**: Number of siblings/spouses aboard
- **parch**: Number of parents/children aboard
- **fare**: Fare paid for the ticket
- **survived**: Survival status (1 = Survived, 0 = Did not survive)

The dataset used here is a cleaned version of the Titanic dataset, where missing values have been dropped, and the categorical variable `sex` has been encoded into numerical values (0 for Female, 1 for Male).

## Model
A **Linear Regression** model is used to predict survival probabilities. Although logistic regression is often more suited for binary classification problems, this project uses linear regression for educational purposes.

### Independent Variables (Features):
- Passenger class (`pclass`)
- Gender (`sex`)
- Age (`age`)
- Number of siblings/spouses aboard (`sibsp`)
- Number of parents/children aboard (`parch`)
- Fare (`fare`)

### Dependent Variable (Target):
- Survival (`survived`)

## Project Structure


## Requirements
To run this project, you need the following dependencies, which are listed in the `requirements.txt` file:
- pandas
- scikit-learn

## how to run
You can install the dependencies using:
```bash
pip install -r requirements.txt


git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction
pip install -r requirements.txt

