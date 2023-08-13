# Car-Price-Prediction-using-Machine-Learning-Techniques
Problem Statement:

The price of a car is dependent on the features it offers, such as the model, mileage, fuel type, and interior. The objective of this problem is to predict the price of a car based on its features. By doing so, we can estimate the cost of a car based on its characteristics and provide a good estimate of the price range it falls in. This prediction model can help in establishing transparency between car sellers and buyers in the market. Consumers can know the actual worth of a car or a desired car by providing the program with a set of attributes to predict the car's price. This can help consumers make informed decisions while buying or selling cars. We aim to use machine learning techniques to analyze and understand the various factors that influence car prices and build a predictive model that accurately predicts car prices based on these factors. 
Motivation:
The main motivation behind this project is to promote transparency in the car market and empower buyers to make informed decisions by predicting the actual worth of a car based on a set of attributes provided to the program.

Methodologies:

Data Collection:

The Car Price Prediction dataset, which can be found on Kaggle, consists of 19237 rows and 18 columns. The dataset contains a variety of descriptive features, including continuous and categorical variables. The target feature, "Price," is a continuous variable, while the remaining columns describe the car's characteristics, such as the manufacturer, model, category, leather interior, fuel type, and gearbox type, to name a few. 

Data Preprocessing:

•	In data preprocessing we have to replace ‘-’ values in the levy feature with NAN values.
•	Converting the features with extra characters such as ‘km’ by stripping them from data.
•	Replace the garbage values.

Data Exploration:

•	Generating Data quality reports for Continuous features and Categorical features.
•	Generating Bar Plots and Histograms to look at the distribution of the Categorical features and Continuous features to understand our data.
•	Using IQR method to detect outliers in Levy, Mileage and Engine volume features

Feature Selection:

•	Performing the correlation test to measure the linear relationship between 2 or more variables for Continuous features and Categorical features. Through correlation, we can predict one variable from the other.
•	Feature selection using Information gain: calculating Information gain of the features using Entropy and Gini index.

Scaling:

•	Normalization:
Using Standard Scaler as our normalization technique.
•	Transformation:
Using One-Hot Encoding to encode the categorical features.

Model Building:

Predicting the price of a car given the features is a regression problem. So, we will be using the following regression algorithms:

•	Linear Regression 
•	K-Nearest Neighbours(KNN) 
•	ADA boost classifier 
•	Support Vector Regression(SVR) 
•	Random forest Regressor

Evaluation metrics:

Using RMSE as the unit of the error would be the same as the target feature which makes it easier to interpret the results.



