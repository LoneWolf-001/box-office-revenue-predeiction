# box-office-revenue-prediction
Using the TMDB Box Office dataset to predict revenue of a movie

This is my first Machine Learning Project. I used regression based models like Linear Regression, Random Forest Regressor and XGBoost to predict 
revenue of a movie using various features like budget, runtime, popularity, genre-count, language-count, cast-count, crew-count etc.

First I cleaned the data, filled missing values, used time series analysis to make the date column usable and also one-hot encoded the categorical data.
Then I tried to visualise the data using Matplotlib and Seaborn libraries.
Finally I fit the models and found that Random Forest Regressor gives the best results with a r2 score of 0.54

Thanks
