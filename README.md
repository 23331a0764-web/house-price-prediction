Boston Housing Price Prediction

This project builds a Linear Regression model to predict housing prices using the Boston Housing dataset. The model is implemented using Python and machine learning libraries such as scikit-learn, NumPy, Matplotlib, and Seaborn.

The model predicts the median house value (MEDV) based on selected housing features.

Dataset

The dataset used in this project is the Boston Housing dataset.

Features used in the model:

RM – Average number of rooms per dwelling

LSTAT – Percentage of lower status population

PTRATIO – Pupil-teacher ratio by town

Target variable:

MEDV – Median value of owner-occupied homes

Dataset source:
https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv

Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

scikit-learn

Google Colab

Machine Learning Model

The project uses Linear Regression to predict house prices.

Steps involved:

Import required libraries

Load the dataset

Check for missing values

Select relevant features

Split the dataset into training and testing sets

Train the Linear Regression model

Predict house prices

Evaluate model performance

Model Evaluation

Two metrics are used to evaluate the model:

Mean Squared Error (MSE)

R² Score

Example results:

Mean Squared Error: 27.11
R² Score: 0.63

This indicates the model explains around 63% of the variance in housing prices.

Visualization

A scatter plot is used to compare Actual vs Predicted house prices.

X-axis → Actual values

Y-axis → Predicted values

This helps visualize how well the model predictions match real values.

How to Run the Project

Clone the repository

git clone https://github.com/yourusername/boston-housing-prediction.git

Navigate to the project folder

cd boston-housing-prediction

Install required libraries

pip install numpy pandas matplotlib seaborn scikit-learn

Run the Python script or open the notebook in Google Colab.

Project Structure
boston-housing-prediction
│
├── Boston.csv
├── housing_prediction.ipynb
├── README.md
