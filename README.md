# Adult-Census-Income-Prediction-


This data was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1) && (HRSWK>0)).
The prediction task is to determine whether a person makes over $50K a year.

DATA DEFINATION
The Adult's Income dataset is collected from kaggle using this https://www.kaggle.com/uciml/adult-census-income.
This dataset has 48842 rows × 15 columns.

1- age: continuous.
2 - workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
3 - fnlwgt: continuous.
4 - education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
5 - education-num: continuous.
6 - marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
7- occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
8 - relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
9 - race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
10 - sex: Female, Male.
11 - capital-gain: continuous.
12 - capital-loss: continuous.
13 - hours-per-week: continuous.
14 - native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.


METHODS
In this project, we have employed the following steps:

Data Collection
Data Cleaning
Data Analysis
Data Preprocessing(Preparation)
Model Training
Performance Evaluation
We have implemented the following models:

SVM
Logistic Regression
Naive Bayes
PERFORMANCE EVALUATION
We have calculated the performance by calculating Precision, Recall , True positive/negative for all the models and built a Confusion Matrix for the same.

# Project Name

[Project Description]

## Table of Contents

- [Project Overview](#project-overview)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Methods](#methods)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

[Provide a brief overview of your project, including its goals and objectives.]

## Data

[Describe the data used in your project. Mention the source, size, and any preprocessing steps if applicable.]

## Installation

[Provide instructions on how to install any dependencies required for your project.]

```bash
pip install -r requirements.txt


