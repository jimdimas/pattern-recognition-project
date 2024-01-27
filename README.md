# Hello and welcome to my repo for my Pattern Recognition Final Assignment.

## Introduction

In this assignment we are given a dataset comprised of features about houses , derived from a surver done in 1990 in the state of California,USA. <br />

More specifically , our dataset is comprised of the following features: <br />

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity
- Median House Value (target feature,known beforehand)

The Population,Households and Median Income features refer to the local area of the house. <br />

Our goal is to: <br />

1. Preprocess the dataset
2. Make visualizations on the data and find trends/correlations etc.
3. Create the following classifiers:

- Perceptron
- Least Square
- Neural Network

We will implement the Perceptron and Least Square classifiers with custom functions. <br />

In the case of the Perceptron classifier , we will set a threshold of the Median House Value and split the dataset in two classes and <br />
then make this a binary classification problem by creating a new binary feature (e.g. isExpensive -> Median House Value of house >< Median of Median House Values) .<br />

In the end we will compare the performance of each model.

## Required modules

In this project I will be using Jupyter Notebook format to visualize the data while providing the code as well. <br />
The required python modules are: <br />

- pandas
- numpy
- matplotlib
