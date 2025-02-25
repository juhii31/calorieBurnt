# calorieBurnt
This project uses an XGBoost Regression model to predict calorie expenditure from exercise. The model is trained on a dataset containing various features like gender, age, height, weight, and exercise intensity metrics to predict the number of calories burned.
Dataset
The project uses two datasets:

exercise_dataset.csv: Contains features related to the user and their exercise.
calories.csv: Contains the target variable (calories burned).

Features

User_ID: Unique identifier for each user
Gender: Male or female
Age: Age of the user in years
Height: Height of the user (likely in cm)
Weight: Weight of the user (likely in kg)
Additional exercise-related metrics (heart rate, exercise duration, etc.)

Dependencies

Python 3.x
NumPy
Pandas
Matplotlib
Seaborn
scikit-learn
XGBoost
