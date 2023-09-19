# Price of House Prediction
> Leveraging data analytics, we aimed to optimize property investments by developing a robust regression model using **regularization** techniques. The objective was to accurately predict property values, enabling strategic investment decisions. Developed a powerful regression model leveraging **Ridge** and **Lasso** Regression to predict property values accurately.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- This project addresses Surprise Housing, a US-based company entering the Australian housing market. Leveraging data analytics, we developed an advanced regression model employing Ridge and Lasso Regression to predict property values accurately. Our goal is to aid strategic investment decisions by identifying significant variables **influencing house prices**.
- Surprise Housing aims to purchase properties in Australia below market value and resell them at a higher price. To achieve this, they've collected a dataset from **Australian house sales**. The project focuses on building a regression model to predict property values and guide investment choices.
- The key challenge is to predict house **prices accurately**, enabling the company to decide on prospective property investments. Understanding the variables significantly affecting house prices and their impact is crucial. The project addresses this problem using advanced regression techniques.
- The dataset comprises sales data of houses in Australia. It includes various features such as house area, overall quality, neighborhood, and more. The target variable is **'SalePrice,'** representing the house's sale price. This dataset is crucial for training and validating our regression models.



## Conclusions
- The target variable, SalePrice, demonstrates a strong correlation with features like **GrLivArea, GarageCars, and GarageArea**.
- Increasing alpha leads to a reduction in train error initially, followed by a decline in test error. The graph clearly indicates an optimal **alpha value of 10**.
- Incrementing alpha results in decreasing train and test errors; however, beyond an error value of approximately **0.05**, the error stabilizes.
- Key variables significantly **affecting house price** prediction include GrLivArea, OverallQual, OverallCond, Neighborhood, Functional, Exterior1st, SaleCondition, CentralAir, TotalBsmtSF, and Condition1.




## Technologies Used
- **numpy** - version 1.21.3
- **pandas** - version 1.5.3
- **matplotlib** - version 3.4.3
- **seaborn** - version 0.12.2
- **sklearn** - version 1.2.1



## Acknowledgements
Give credit here.
Give credit here.
- The training provided by **IIIT Bangalore** greatly contributed to the successful execution of this project.
- This project was based on [this tutorial](https://learn.upgrad.com/course/4617/segment/27466/242409/740997/3737983).



## Contact
Created by [@mayur200] - feel free to contact me!


