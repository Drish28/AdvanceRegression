#Regression Model Approach for Surprise Housing in the Australian Market


## Business Goal

The ultimate goal is to create a robust model that accurately captures the dynamic relationship between independent variables and house prices. This model will serve as a valuable tool for management, enabling a nuanced understanding of price variations and empowering strategic decision-making. By concentrating efforts on areas with high return potential, Surprise Housing aims to optimize its investment strategy in the Australian market. Furthermore, the model will provide insights into the unique pricing dynamics of this new market, offering a comprehensive understanding for effective market penetration and sustained success.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->


## Conclusions

1. The Ridge Regression model was optimized with a lambda value of 5.0.
2. Lasso Regression achieved its optimal performance with a lambda value of 0.001.
3. Utilizing Ridge Regression:
   1. The model indicates that `Total_Sqr_Footage`, `GrLivArea`, and `TotalBsmtSF` exert the highest positive impact on estimating the sale price of a house.
   2. Positive contributions to the prediction of sale price also come from features like `Total_Bathrooms`, `LotArea`, `OverallQual_Very Excellent`, and `OverallQual_Very Good`, albeit with slightly lower coefficients.
   3. Neighborhood characteristics, specifically `Neighborhood_StoneBr` and `Neighborhood_Crawfor`, significantly influence the determination of house sale prices.
   4. The `OverallCond_Excellent` feature, representing the overall excellent condition of the house, positively influences the predicted sale price.
4. Employing Lasso Regression:
   1. The model highlights the importance of features such as `Total_Sqr_Footage`, `GrLivArea`, and `BsmtUnfSF` in positively impacting the estimation of house sale prices.
   2. Crucial factors influencing sale prices include `OverallQual_Very Excellent` and `OverallQual_Excellent`, both exhibiting substantial positive coefficients.
   3. The presence of the `SaleType_New` feature positively contributes to the predicted sale price, indicating a notable impact from this particular sale type.
   4. Additional positive contributors to the prediction of sale price include features like `OverallQual_Very Good`, `GarageCars`, `Total_Bathrooms`, and `LotArea`, although with slightly lower coefficients.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
[Python](https://www.python.org/) - version 3.11.4
- [Matplotlib](https://matplotlib.org/) - version 3.7.1
- [Numpy](https://numpy.org/) - version 1.24.3
- [Pandas](https://pandas.pydata.org/) - version 1.5.3
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2
- [Scikit-Learn](https://scikit-learn.org/stable/) - version 1.3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- UpGrad tutorials on Advanced Regression on the learning platform


## Contact
Created by [@Drish28] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->