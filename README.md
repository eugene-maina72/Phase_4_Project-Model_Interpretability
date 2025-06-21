# Phase_4_Project-Model_Interpretability

This is a repository that aims to build a model to predict the cause of road accidents.

## OVERVIEW

### Business Problem

![Flag of Chicago, Illinois](images/Flag_of_Chicago,_Illinois.svg)

* The City of Chicago Traffic Safety Board would like to gain further insights into the primary contributory causes of road accidents in the city to help develop targeted interventions. The objective is to build a model that can predict the primary contributory cause of a car accident, given information about the car, the people in the car, the road condition, etc.

* As per Illinois statute, only crashes with a property damage value of $1,500 or more or involving bodily injury to any person(s) and that happen on a public roadway and that involve at least one moving vehicle, except bike dooring, are considered reportable crashes.

* The overall main business questions are:

1. What are the top 10 primary contributors to road accidents?
2. What accidents cause the most fatalities?
3. What period do accidents commonly occur by month?

## THE DATA

* The dataset can be found on [Chicago Data Portal](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if/about_data)

## METHODS

1. **Logistic Regression:**  
  Simple and interpretable, but limited in capturing complex relationships in the data.

2. **Decision Tree:**  
  Offers interpretability and some improvement, but can overfit and is less stable.

3. **Random Forest:**  
  Better generalization, handles feature interactions, and provides useful feature importances.

4. **XGBoost:**  
  Best overall performance, robust to class imbalance, and effective for large, complex datasets.

5. **KNN:**  
  Underperforms due to high dimensionality and class imbalance; not recommended for this problem.

```
The contents of the repo are:
            -data
            -images
            -gitignore
            -notebook
            -Non-technical presentation
            -README.md

The dependencies are:
            -Numpy
            -Pandas
            -sklearn
            -imblearn
            -matplotlib
            -seaborn
            -statsmodels
            -catboost
            -xgboost
            -eli5
```

You can reach the authors at:
