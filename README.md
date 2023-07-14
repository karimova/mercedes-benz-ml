# Mercedes-Benz Testing Time Prediction
<img src="p-7.jpg" alt="Mercedes-Benz" width="600">

## Description

Reduce the time a Mercedes-Benz spends on the test bench.

## Problem Statement Scenario

Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include the passenger safety cell with a crumple zone, the airbag, and intelligent assistance systems. Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium carmakers. Mercedes-Benz is the leader in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams.

To ensure the safety and reliability of every unique car configuration before they hit the road, the company’s engineers have developed a robust testing system. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Mercedes-Benz’s production lines. However, optimizing the speed of their testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach.

I am tasked with reducing the time that cars spend on the test bench. I will be working with a dataset representing different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. By developing optimal algorithms, I aim to contribute to faster testing, resulting in lower carbon dioxide emissions without reducing Mercedes-Benz’s standards.

## Actions to Perform

- Removal of Variables with Zero Variance: I removed any column(s) in the dataset where the variance was equal to zero.
- Checking for Null and Unique Values: I checked the test and train sets for any null values or unique values.
- Preprocessing Categorical Features: I performed preprocessing on the categorical features in the dataset to prepare them for further analysis. This likely included encoding categorical variables into numerical representations.
- Dimensionality Reduction: I applied dimensionality reduction techniques to reduce the number of features in the dataset. This step helps in eliminating redundant or less informative features, improving computational efficiency, and reducing the risk of overfitting.
- Prediction using XGBoost: I used the XGBoost algorithm to predict the values of the test_df dataset. XGBoost is a powerful gradient boosting algorithm commonly used for regression and classification tasks.

By completing these steps, I have processed the data, handled missing values, transformed categorical features, reduced the dimensionality, and made predictions using XGBoost for the test dataset.

## Dataset

Find the datasets [here](https://example.com/path/to/dataset).

