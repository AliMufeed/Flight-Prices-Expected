## Flight Prices Expectation

The goal of this project is to predict the price of flight from deferent locations to Riyadh in January 2022. Using Selenium, 3789 rows and 12 columns 
have been scraped from Almosafer.com for 8 different countries which represent the dataset. The 12 columns are the feature that will affect the price, 
such as the flight duration, time of landing and arriving, wight of the baggage and day of month.

![heatmap](https://user-images.githubusercontent.com/90555117/138132769-b6d54c87-999f-4241-9c5c-b066b6f3abde.png)

The figure above, is a heatmap plot that represent the correlation between the features (columns) and the target which is the price in this case. Also,
the figure shows that the flight duration has the highest correlation among features with the target. However, wight of baggage and day of month have 
almost no effect in the price.

The result from the above figure is not enough to start building regression modules, in other word, the numerical values need to be increased, such as, 
number of stops. Also, the days should be divided into weekday and weekend. The next step will be creating extra numerical features then clean the 
dataset by removing outliers, nulls and duplicate. After that, different regression models will be built starting from linear regression, polynomial 
regression with different degrees, ridge regression, lasso regression and elastic regression, to decide with one is the best in term of R^2.
