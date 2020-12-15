# ML-Final-Project

This project aims to find a better solution with time series method and regression method to assess the temporal structure of cases, demographic and economic influence on the spread of COVID-19 virus. Dataset from CDC is chosen as the main source and further everyday protest nunmber, Dow Jones Index and traveler number through 2020 are added as interested features.

For the time series method, we see the model's performance gets significantly increased after applying time series model to our baseline--linear model.

For the tree regression and random forest regression, we find that the over-fitting method (tree regression) may ocassionally perform better than random forest, which even increase this model's degree of under-fitting. However, both regression methods lead to unstable errors which we believe are limited by our data--the number of samples in the dataset is bound to the number of days after quarantine.

For more details, please feel free to run the notebook kw.ipynb to see what we've learned from this project.
