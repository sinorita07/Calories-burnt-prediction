# Calories-burnt-prediction
Machine Learning Project 
In my Calories Burnt Prediction project, I predicted the number of calories burnt during exercise using machine learning. I combined exercise and calorie data from two CSV files, performed exploratory data analysis with Matplotlib and Seaborn, and converted categorical data into numerical values. I split the dataset into training and testing sets and used XGBoost Regressor for model training due to its efficiency and accuracy. The model achieved a low Mean Absolute Error (MAE) of 1.48, indicating high accuracy. I also built a predictive system that takes input features and accurately predicts calories burnt, showcasing my skills in data preprocessing, visualization, and model training.

The PDF contains step-by-step process of the Project 

To check the accuracy if the project include the following statements:
from sklearn.metrics import r2_score

# Assuming you have the test data predictions and the actual test values
r2 = r2_score(Y_test, test_data_prediction)
print("R-squared value:", r2)
