# PRODIGY_ML_01
House Price Prediction using Linear Regression

1.Project Description
This project focuses on predicting house sale prices using a linear regression model. The model is trained on the Ames Housing dataset, which contains various features related to residential homes. The goal is to build a model that can accurately estimate house prices based on these features.

2.Dataset
The dataset used in this project is the Ames Housing dataset, obtained from Kaggle: [Insert Kaggle Dataset Link Here]

3.Libraries Used

* pandas
* numpy
* matplotlib
* scikit-learn
* seaborn

4.Data Preprocessing

* Loaded the dataset using `pandas`.
* Selected relevant features: `LotArea`, `YearBuilt`, `FullBath`, `RoofStyle`, `KitchenAbvGr`, `BedroomAbvGr`, `TotRmsAbvGrd`.
* Encoded the `RoofStyle` categorical feature into numerical values.
* Removed outliers from numerical features and the target variable (`SalePrice`) using the Interquartile Range (IQR) method.
* Renamed columns for readability.

5. Model Training

* Split the data into training and testing sets using `train_test_split`.
* Standardized the features using `StandardScaler`.
* Trained a linear regression model using `LinearRegression`.

## Model Evaluation

* Evaluated the model's performance using the R-squared score and Mean Absolute Error (MAE).
* R-squared score: 0.64
* Mean Absolute Error: 34125.63
