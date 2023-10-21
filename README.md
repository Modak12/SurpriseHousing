# Surprise Housing
> To predict the actual value of the prospective properties and decide whether to invest in them or not.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

- The company is looking at prospective properties to buy to enter the market. It is required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

    - The company wants to know:

        - Which variables are significant in predicting the price of a house, and

        - How well those variables describe the price of a house.

    - Also, determine the optimal value of lambda for ridge and lasso regression

- To model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions
- Optimal value of alpha in Ridge : 4

- Optimal value of aplha in Lasso : 0.001

- Top 10 features in Ridge Regression with their cofficients :
    - RoofMatl_CompShg    0.275774
    - RoofMatl_Tar&Grv    0.183106
    - RoofMatl_WdShngl    0.137018
    - MSZoning_RL         0.134376
    - RoofMatl_WdShake    0.113699
    - MSZoning_RM         0.101120
    - GrLivArea           0.075785
    - MSZoning_FV         0.068683
    - RoofMatl_Membran    0.062715
    - RoofMatl_Metal      0.059642

- Top 10 features in Lasso Regression with their cofficients :
    - RoofMatl_CompShg    0.242023
    - RoofMatl_Tar&Grv    0.162588
    - GrLivArea           0.142040
    - RoofMatl_WdShngl    0.121258
    - RoofMatl_WdShake    0.101795
    - MSZoning_RL         0.074449
    - OverallQual         0.066269
    - RoofMatl_Membran    0.052098
    - RoofMatl_Metal      0.050648
    - RoofMatl_Roll       0.048608


## Technologies Used
- python 3.0


## Acknowledgements
This project was a problem statement given by IIIT-B for the cohort course of ML-AI.


## Contact
Created by [@Modak12] - feel free to contact me!
