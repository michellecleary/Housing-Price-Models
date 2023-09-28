# Modelling Housing Prices

Statistical case study carried out as a group project at the University of Edinburgh.

Datasets: \\
-Dataset 1: housing data for an American city, including 29 house features.\\
-Dataset 2: housing data for an American city, including the same features as Dataset 1, along with an additional 52 features.

Report 1: This report evaluates the performance of two classification models at predicting whether a house will sell for above or below the average market price. Firstly, a logistic regression model is implemented, using all 29 available features in Dataset 1. Then, a Naive Bayes model using only five features from Dataset 1 was fitted. Model performance was evaluated using accuracy under 10-fold cross-validation.

Report 2: This report evaluates the performance of 5 quantitative models at predicting the sale price of a house based on information about the property. A linear regression model using the 29 available features from Dataset 1 is implemented. Then, variable selection is performed and another linear regression model is fitted, using only the 3 features from Dataset 1 which have the biggest impact on sale price. Finally, three further models are fitted using all 81 features in Dataset 2 to investigate whether these
extra features have any benefit in predicting sale price. A simple linear regression, a lasso regression, and a random forest were implemented. Model perofrmance was evaluated throughout using mean absolute error under leave-one-out cross-validation.
