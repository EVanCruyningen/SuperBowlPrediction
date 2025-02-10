# SuperBowlPrediction

The goal of this project is to predict the 2025 Super Bowl score using historical data. We selected the past fifteen Super Bowls as our dataset and pulled the data using the free SportsRadar API. We began by pulling all of the last fifteen Super Bowl winners and their statistics for the season that they competed in the Super Bowl. We then pulled the final scores of those Super Bowl games and trained multiple models to optimize our R squared and mean squared error (MSE). Models we tried include: Linear Regression, XGBoost, Random Forest Regression, and a small Neural Network. 

Our best model was an XGBoost Regressor after we did feature selection using another XGBoost Refressor. We found the optimal number of features to be 27 of our ~400 features and with hyperparameter tuning we were able to get a 0.485 R-squared value with a 34.72 mean squared error. We then predicted the Super Bowl score for the upcoming Chiefs and Eagles game and found the end score to be 18.48 points for the Eagles, and 25.0 points for the chiefs. Using domain knowledge, we are approximating the final score to be Eagles 17, Chiefs 24.

After Super Bowl update: I think no model could have ever predicted that game. I do believe that our error was high and our model was not perfect, but predicting a game like that would make me think the prediciton was wrong. Either way, a fun project to have done!

-Erik Van Cruyningen 
-Bhuvan Balagar
