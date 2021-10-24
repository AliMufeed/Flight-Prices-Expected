## Flight Prices Expectation

The goal of this project is to predict the price of flight from deferent locations to Riyadh in first week of December 2021. Using Selenium, 3986 rows and 13 columns 
have been scraped from Almosafer.com for 11 different countries in Eorupe which represent the dataset. 12 columns out of 13 are the feature that will affect the price, 
such as the flight duration, time of Take-off and arriving, wight of the baggage and day of week.

![heatmap](https://user-images.githubusercontent.com/36573740/138600454-c2386d57-3ade-4ff0-a1e5-bf5c39a48844.png)

The figure above,  represent the relation between the day of week and the average price for the Economy and Business class. the figure shows that is the highest flight prices will be in the Saturday because it is common weekend in Europe and Saudi Arabia
Also, the figure represent that the flight prices decrease  in Monday (weekday)  so these days will effect on the price and make big change.

##
![image](https://user-images.githubusercontent.com/90555117/138605217-1764cb87-7a58-4d05-971b-3606476cb9e2.png)

The second figure shows the corrilation between the numarical values in the DataFrame, and represent the affect of changing the value of the feature (Duration_Minutes) on the target which is the price (Price_NEW) in this case. Also,
the figure shows that the flight duration has nigative correlation with the target, so as the duration of the flight increase the price decrease.

The result from the above figure is not enough to start building regression modules, in other word, the numerical values need to be increased, such as, 
number of stops. Also, the days should be divided into weekday and weekend. The next step will be creating extra numerical features then clean the 
dataset by removing outliers, nulls and duplicate. After that, different regression models will be built starting from linear regression, polynomial 
regression with different degrees, ridge regression, lasso regression, elastic regression, and other regression models to decide with one is the best in term of R^2.
