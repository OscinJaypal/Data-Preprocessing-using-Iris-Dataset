# Data-Preprocessing-using-Iris-Dataset
Operations-for-Data-Preprocessing-using-Iris-Dataset Basic operations performed for understanding the concept data preprocessing. Dataset used : http://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data

## Overview
Data preprocessing is a crucial step in the data science pipeline. It involves transforming raw data into a format suitable for modeling. The Iris dataset, a classic dataset in machine learning, contains measurements of iris flowers from three different species. This dataset is often used to illustrate basic techniques in data preprocessing and machine learning.

## Iris Dataset Description
The Iris dataset consists of 150 samples from three species of Iris flowers: Iris setosa, Iris versicolor, and Iris virginica. Each sample has four features:

1. Sepal length (in cm)
2. Sepal width (in cm)
3. Petal length (in cm)
4. Petal width (in cm)
Additionally, there is a target column indicating the species of each sample.

## Methodology for Data Preprocessing
1.	Data Loading: Load the dataset into a Pandas DataFrame.
2.	Data Exploration: Explore the dataset for structure, summary statistics, and missing values.
3.	Data Cleaning: Handle missing values, duplicates, and inconsistencies (if any).
4.	Feature Engineering: Create or transform features (minimal for the Iris dataset).
5.	Encoding Categorical Variables: Encode target variable into numerical values.
6.	Feature Scaling: Standardize the range of independent variables using a scaler.
7.	Splitting Data: Split the data into training and testing sets for model evaluation.

## Required Libraries
Numpy
Pandas
Matplotlib
