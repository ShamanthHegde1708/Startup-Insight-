Startup Insight Program
Author: Shamanth Hegde
Date: 16-07-2025

This tool uses multiple linear regression to predict a startup's profit based on various expenses and location.

Features:

1.Loads startup data from a CSV file (50_Startups.csv)

2.Encodes the "State" column using OneHotEncoding

3.Splits the dataset into training and test sets

4.Trains a multiple linear regression model

5.Predicts startup profit based on input features

6.Optionally applies backward elimination to improve accuracy

How to Use:

1.Make sure the 50_Startups.csv file is in the same folder as your script
(It must contain these columns: R&D Spend, Administration, Marketing Spend, State, and Profit)

2.Run the script:
python startup_insight.py

3.The script will:

4.Train the model

5.Predict profits

6.Print actual vs predicted values
