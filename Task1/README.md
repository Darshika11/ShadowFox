Boston House Price Prediction using Machine Learning

Objective
The objective of this project is to develop a machine learning model that predicts house prices in Boston based on various housing features such as crime rate, number of rooms, property tax rate, and other socio-economic factors.


Dataset
The dataset used in this project is HousingData.csv, which contains multiple features related to housing conditions and neighborhood characteristics. The target variable is MEDV, representing the median value of owner-occupied homes.
Technologies Used
•	Python
•	Pandas
•	NumPy
•	Scikit-Learn
•	Matplotlib
•	Seaborn



Machine Learning Models
Two regression models were implemented:
1.	Linear Regression – Used as a baseline model.
2.	Random Forest Regressor – Used to improve prediction accuracy.
Model Performance
The Random Forest model provided better performance compared to Linear Regression.
Example metrics obtained:
•	MAE: ~2.06
•	MSE: ~8.22
•	R² Score: ~0.88
This indicates that the model explains approximately 88% of the variance in housing prices.


Key Insights
Feature importance analysis showed that the most influential features affecting house prices are:
•	RM – Average number of rooms per dwelling
•	LSTAT – Percentage of lower status population
•	DIS – Distance to employment centers
These factors significantly impact the value of houses.

Author
Darshika Morye
ShadowFox AI/ML Internship
________________________________________



