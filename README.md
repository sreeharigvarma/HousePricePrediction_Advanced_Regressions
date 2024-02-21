# HousePricePrediction_Advanced_Regressions
Advanced Linear Regression performed on the Surprise Housing dataset as part of an assignment for coursework for PG in Machine Learning and AI from IIIT Bangalore.


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Advanced linear regression is performed on the dataset to predict "Sales_Price". The focus is on solving complexity issues of the model using regularisation.
- The project is done as part of coursework in the Machine Learning chapter. 
- We are trying to model the price of houses with the available 81 independent variables. 
- The Surprise Housing dataset is being used. 
- Regularization is focused on this dataset with ridge and lasso regression used. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
* We have cleaned and visualized the data, treated for outlier and imputed values as and when required and prepared the model for training. 

* As we can see there is not much difference in the model performances in the three cases, however lasso regression model performs ever so slightly better than the other two models. The most important predictor values determined from the analysis were as follows-
1. RoofMatl_WdShngl : 0.655780
2. Neighborhood_NridgHt : 0.499205
3. Neighborhood_NoRidge : 0.466566
4. Neighborhood_StoneBr : 0.381173
5. GrLivArea : 0.369273


## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
sreeharipkgvarma@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->
