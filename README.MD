# Apartment for sale price predictor

This project is a part 6 months Data Science bootcamp - Sages [Kodołamacz Data Science Bootcamp](https://www.kodolamacz.pl/bootcamp-datascience/), which I took part September 2019 - March 2020.


## Overview

This machine learning project predicts price of apartment for sales in Kraków.


## Data
All data sets come from [otodom.pl](https://www.otodom.pl/) and were restricted only to Kraków location (end of Feb'20).


## Dependencies

* Python 3.6
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Sklearn
* String
* Re
* Warnings
* Selenium
* IPython


## Action plan

After scrapping data, all is cleared and some addtional features are added to manage to estimation in the correct way. Then several estimator are validated to find the best aproximation.


## Scope of work

1. '01. Webscrapping_apartments for sale'
2. '02. Price_estimation'


## Final results

As expected the best estimator is Gradient Boosting with defined parameters max_depth: 95, min_samples_leaf: 15, n_estimators: 150. The results is not an amazing achievement 

$R^2$ score = 0.63

MSE = 9.375760e+10

RMSE = 306198.6
