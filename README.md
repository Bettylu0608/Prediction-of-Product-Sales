# Prediction-of-Product-Sales


The percentage of sales for both Low Fat and Regular products



The amount of Item Outlet Sales per number of item.
Sales prediction for food items sold at various stores.

Author: Grecia Lopez

Business problem:
Analyzing Item Outlet sales

Data:
/content/drive/MyDrive/CodingDojo/01-Fundamentals/Week02/Data/sales_predictions_2023.csv

For this dataset, there were 8523 rows and 12 columns

Data Dictionary
![image](https://github.com/Bettylu0608/Prediction-of-Product-Sales/assets/144574544/6a793cef-f3d7-44bd-a2a8-8ff2ef896696)


Methods
We cleaned the data, searched for any inconsistent or missing values.
Then we created a histogram and a barplot.

Item Type vs. Item Outlet Sales
![image](https://github.com/Bettylu0608/Prediction-of-Product-Sales/assets/144574544/78b66019-3926-44f3-9e55-2e0c37d10bb5)

Sales/assets/144574544/c131d23f-ebf8-4523-b14c-767e15314330)
Percentage of sales for both Low Fat and Regular products
![image](https://github.com/Bettylu0608/Prediction-of-Product-Sales/assets/144574544/f40767dc-0e93-4d70-9e16-a4ef1f35c9e5)

Machine Learning Using the Following Models:

-Linear Regression Model

-Random Forest Regressor Model

Model Results

Linear Regression Model (Testing Set):

R^2: 0.502
MAE: 879.869
MSE: 1,385,263.296
RMSE: 1,176.972

Random Forest Regressor Model (Testing Set):

R^2: 0.554
MAE: 774.320
MSE: 1,240,470.977
RMSE: 1,113.764

Tuned Random Forest Regressor Model (Testing Set):

R^2: 0.554
MAE: 774.320
MSE: 1,240,470.977
RMSE: 1,113.764


The model chosen was Random Forest Regressor Model. 

55.4% of the variance in y was explained by x.

The Mean Absolue Error was off by about $774.32.

The Mean Squared Error was $1,240,470.97.

The Root Mean Square Error had a calculation of $ 1,113.76

Both of these models were not very reliable for making predictions. 

For the Linear Regression Model these were the top 3 Most impactful features:

![image](https://github.com/Bettylu0608/Prediction-of-Product-Sales/assets/144574544/46e19f3b-8ae0-417e-86d1-34046a8e3fd4)

Top 3 Most Impactful Features
1. Outlet Type Supermarket Type 3
2. Outlet Identifier
3. Outlet establishment Year

For the Random Forest Model these were the 5 most important features:

![image](https://github.com/Bettylu0608/Prediction-of-Product-Sales/assets/144574544/aa49f047-9d37-49ee-8340-df4832349eea)


1. Item Type Breakfast
2. Item Type Breads
3. Outlet Type Supermarket Type 1
4. Outlet Identifier
5. Item Type Seafood







