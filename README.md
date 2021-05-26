# Jacob St Pierre
## Data Analytics and Data Science Portoflio

## [Prjoect 3 - House Price Prediction](https://github.com/jacobstpierre/Melbourne-Housing-Market)
![](melb_house.png)
### Project OVerview and Problem Statement
The objective of this project is to answer a 2-part problem statement. Firstly can we provide a reliable and feasible recommendation algorithm to predict the average household price in the given dataset.  Lastly can we visualize the correlation between house features and the price to determine which ones affect price the most?

This problem can be solved by creating a reliable and feasible recommendation algorithm to predict the average price of a property in the Melbourne Area. The target value is the data column ‘Price’ within the Melbourne housing market dataset (Melbourne dataset). For predicting the actual price of the house we used the following regression models. 
- Linear Regression
- Random Forest Regressor
- Nearest Neighbours

As we look at each feature and its relaitionship to our target feature 'Price' we will perform some common steps. For each feature we will:
- Visualize the count of variables (where applicable)
- Visualize its relationship to 'Price'
- Remove outliers, and then visualize the vairiable again (where applicable)
     - We have eleceted to use this method in our EDA, rather than when we construct our pipeline. This is because we want to visualize and better understand how removing outliers shapes the data. Also, the method of detecting and removing outliers will depend on the feature.
     - When dealing with outliers we want to preserve as much data as possible. Where possible and when removing outliers by percentile, we will only remove the top 1% of the feature
- Make key observations
    - One of these key observations will be regarding the features suitability for our model
    
### Model Building

In order to simplify using the models, and to better mimic the real world application of models we wil be constructing pipelines to deploy the model. The pipelines, which will be described in more detail in a later section, will all generally follow the same steps:
- __Preprocessing__: In order for the data to be usable in models some preprocessing steps will take place. Here we can apply column transformers, dummy encoding, scaling of numerical features, and encoding ordinal features
- __Feature Selection__: This step will aloow us to perform a streamlines principal companent analysis or a chi2 test to find the most appropriate features for the model
- __Fit__: And the last automated step will be to fit the model to our trainind data

After completeing these steps then we can score and tune the models.


## [Project 2 - Titanic Prediction Model](https://github.com/jacobstpierre/Titanic-Prediction-Model/blob/main/Kaggle%20Titanic%20ML.ipynb)
First run through of the Kaggle Titanic Competition. The goal here is simple, use machine learning to create a model that predicts which passengers survived the Titanic shipwreck. Part of what had initially interested me in this competition, apart from practicing machine leanring techniques and skills, was the opportunity for an indepth exploratory data analysis.

## [Project 1 - Bicycle Thefts in Toronto](https://github.com/jacobstpierre/Bicycle-Theft-in-Toronto)
![](bike-thief-cartoon.jpeg =100x20)

Capstone Project for York University Into to Big Data Analytics

This was the first project I completed for the aforementioned course. Working in a team with two other classmates, I took up the task of doing all programming work. I was able to apply my Python knowledge the previous two months I had spent studying and practising Python.

The purpose of this project was to test our abilities not only in programming, but also in project understanding and the CRISP-Decision Model application. In order to complete this project extensive data cleaning was required, as victims were the ones entering thier information, which was often prone to errors. In doing this analysis, I was able to derive insight into which type of bicycle gets stolen, when these thefts are most likely to occur, and the location of these thefts. After doing this anylsis I looked at whether changes in police spending in the division is correlated to a reduction in thefts. While in the reality, bicycle theft is primarily motivated by opportunity, this analysis confirmed that.
