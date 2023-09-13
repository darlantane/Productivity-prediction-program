# Productivity-prediction-program

## Description

A Machine Learning program applying a linear regression model to predict the future performance values of the machines present on the production lines of a workshop, using production reports as a database.

## Getting Started

### Dependencies

Before running the code, make sure you have installed the following Python libraries:

NumPy

Pandas

Scikit-Learn

### Installing

You can install them using pip :

ex. pip install numpy pandas scikit-learn tensorflow

### Executing program

Run the Python script Productivity_with_linear_regression.py.

You will be prompted to enter the name of the line of data you wish to analyze. Choose from the following options: "L12", "L15", "L17", "L48", "L05", "L06", "L08", "L47", "L50".

Next, specify the number of products you wish to analyze.

For each product, enter the product code.

Specify the number of input parameters you wish to use.

For each input parameter, enter its name.

Specify the number of target parameters you wish to use.

For each target parameter, enter its name.

The data will then be normalized and a linear regression model fitted.

You can then make predictions by entering values for the input parameters.

Predictions will be displayed, and you can choose to make further predictions or terminate the program.

### Project structure

Productivity_with_linear_regression.py: The main script containing the code to run the linear regression.

data/ : The directory where the Excel files containing the data per line are located.

## Author

This project was created by Darlan Tane.
