# (Data Analytics 12/2022) Used Cars in Different States

## Problems
* The relationship between state personal per capita income and the state average price of used cars.
* The relationship between used cars' mileage, year, title status, and price.
* Can we change the predictor or use other models to get a more significant relationship?

## Methods
* Use **linear regression** and **scatter plot**.
* Use **multiple linear regression** to find the relation between price and these categories.
* Use **linear regression, ridge regression, decision tree, and random forest**.

## Result
* There is no relationship between state personal per capita income and the state average price of cars.
* Found little relationship between used cars’ mileage year, title status, and price.
* Using mileage, year, title status, brand, and the state's average income as predictors is better.
* The random forest model here is better than the linear model but still not stable.

## Discussion
* Despite good performance on the training set, the random forest's superiority is questionable due to the nature of decision trees.
* Ensemble methods like decision tree bagging show better generalization than single models.
* Using broad car categories instead of specific models for predicting used car prices may lead to model instability and data insufficiency.
* Effective data analysis often requires iterative improvements and more data to address deficiencies in the current model.
