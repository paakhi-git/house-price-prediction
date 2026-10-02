# House Price Prediction

A machine learning project that predicts house sale prices using the Kaggle Iowa housing dataset. Built as part of the Kaggle *Intro to Machine Learning* course.

## What this project does
- Loads the housing data with Pandas
- Selects 20 features about each house (lot area, overall quality, year built, number of rooms, porch and pool area, and others)
- Splits the data into training and validation sets
- Trains a Random Forest Regressor with Scikit-learn
- Checks the model on the validation set using Mean Absolute Error (MAE)
- Retrains on the full data and generates predictions for the Kaggle competition

## Result
- Validation MAE: about $19,700 (average difference between predicted and actual price)

## Tools used
Python, Pandas, Scikit-learn

## Files
- `exercise-machine-learning-competitions.ipynb`: the notebook with all the code

## How to run
Open the notebook on Kaggle and join the "Housing Prices Competition for Kaggle Learn Users" to get the dataset. Run all cells.

## Possible improvements
- Try different feature sets
- Compare with a Decision Tree model
- Handle missing values and add more features
