# What Drives the Price of a Car??
![](images/kurt.jpeg)

## Overview

In this application, we will explore a dataset from Kaggle. 
The goal is to understand what factors make a car more or less expensive. As a result of the analysis, we can provide clear recommendations to the client(s) —a used car dealership— as to what consumers value in a used car.

### CRISP-DM Framework
<center>
    <img src = images/crisp.png width = 50%/>
</center>

To frame the task, throughout the practical applications, we will refer to a standard process in the industry for data projects called CRISP-DM. This process provides a framework for working through a data problem.


## Dataset

This data comes from Kaggle.
The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure the speed of processing.

Path : https://github.com/CoderNBR/Practical-Application-2/blob/main/data/vehicles.csv

The attributes of this data set include:
    -  id: Running Number
    -  region: region information
    -  price: price of the car
    -  year: year of manufacturing
    -  manufacturer: high school, bachelors degree, associates degree, or graduate degree etc
    -  model
    -  condition
    -  cylinders
    -  fuel
    -  odometer
    -  title_status
    -  transmission
    -  VIN
    -  drive
    -  size
    -  type
    -  paint_color
    -  state

## Approach

1. Importing Data
2. Data cleaning
    - Clean the column names if required
    - Duplicate Check and Removal
    - Drop unwanted columns
    - Missing Value Check & Imputation
 
3. Do EDA
4. Outlier Treatment
5. Data Pre-processing
6. Modelling
    - Linear regression    
    - Ridge regression with polynmial features
    - Ridge regression with sequential features
    - Lasso regression with sequential features
7. Evaluation
8. Plotting distribution of residuals
9. Conclusion

## Visualizations

1. [Distribution of Residuals of Ridge Regression with Polynomial Features](https://github.com/CoderNBR/Practical-Application-2/blob/main/images/ResDistRidgeRegwithPF.png)
2. [Distribution of Residuals of Ridge Regression with Sequential Features](https://github.com/CoderNBR/Practical-Application-2/blob/main/images/ResDistRidgeRegwithSF.png)
3. [Distribution of Residuals of Lasso Regression with Sequential Features](https://github.com/CoderNBR/Practical-Application-2/blob/main/images/RedDistLassoRegwithSF.png)
  
## Conclusion & Recommendation

Based on the analysis and results, the best model is the Ridge Regression with polynomial features. The best features for this model are:

1. Year
2. Cylinder
3. Fuel
4. Odometer

## Repository Link (GitHub)

1. [GitHub Link for Project "What Drives the Price of a Car?"](https://github.com/CoderNBR/Practical-Application-2)
2. [Jupyter Notebook](https://github.com/CoderNBR/Practical-Application-2/blob/main/PracticalApplication2.ipynb)








   
