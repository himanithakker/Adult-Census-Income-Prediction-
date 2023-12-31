
# Adult Census Income Prediction

This project focuses on predicting whether an individual's income exceeds $50,000 a year based on a dataset extracted from the 1994 Census Bureau database. The dataset consists of reasonably clean records extracted using specific conditions, and it is available on Kaggle [here](https://www.kaggle.com/uciml/adult-census-income). The dataset contains 48,842 rows and 15 columns, with various features that provide valuable insights for our income prediction task.

## Data Definition

The dataset includes the following features:

1. **Age:** Continuous.
2. **Workclass:** Categories including Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, and Never-worked.
3. **Fnlwgt:** Continuous.
4. **Education:** Categories ranging from Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, to Preschool.
5. **Education-Num:** Continuous.
6. **Marital Status:** Categories including Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, and Married-AF-spouse.
7. **Occupation:** Categories such as Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, and Armed-Forces.
8. **Relationship:** Categories including Wife, Own-child, Husband, Not-in-family, Other-relative, and Unmarried.
9. **Race:** Categories including White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, and Black.
10. **Sex:** Categories of Female and Male.
11. **Capital Gain:** Continuous.
12. **Capital Loss:** Continuous.
13. **Hours Per Week:** Continuous.
14. **Native Country:** Categories of various countries such as United-States, Cambodia, England, Puerto-Rico, Canada, Germany, and many others.

## Methods

This project followed a structured approach:

1. **Data Collection:** We obtained the dataset from Kaggle, ensuring it met specific quality criteria.

2. **Data Cleaning:** Data cleanliness is essential for meaningful analysis. We thoroughly cleaned and preprocessed the dataset to remove inconsistencies and errors.

3. **Data Analysis:** We performed exploratory data analysis to gain insights into the dataset, helping us understand feature distributions, correlations, and potential patterns.

4. **Data Preprocessing (Preparation):** Preparing the data for modeling included handling categorical variables, scaling numerical features, and encoding labels for machine learning algorithms.

5. **Model Training:** We implemented three machine learning models for this classification task: Support Vector Machine (SVM), Logistic Regression, and Naive Bayes.

6. **Performance Evaluation:** Model performance was evaluated using metrics such as Precision, Recall, True Positives, True Negatives, and the creation of Confusion Matrices to assess the quality of predictions.

## Performance Evaluation

We rigorously assessed the performance of our models:

- **Precision:** Measuring the accuracy of positive predictions.
- **Recall:** Evaluating the ability to identify all positive cases.
- **True Positives/Negatives:** Providing insights into the accuracy of predictions in a binary classification context.

## Conclusion

This project was a fascinating exploration into the world of data science and machine learning. We successfully predicted income levels using various machine learning algorithms and evaluated their performance comprehensively. The insights gained from this project can be applied to real-world scenarios and decision-making processes.

If you're interested in discussing this project further or connecting to explore data science and machine learning, please feel free to reach out. Thank you for your interest!


