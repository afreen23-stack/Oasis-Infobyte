# Car Price Prediction (Used Cars)

## Objective

The objective of this project is to build a machine learning model that can predict the selling price of used cars based on various factors such as year of manufacture, fuel type, transmission type, and number of kilometers driven.

## Dataset

The dataset contains information about used cars and their selling prices. The main features included in the dataset are:

* **Car_Name** – Name of the car
* **Year** – Manufacturing year of the car
* **Selling_Price** – Selling price of the car (target variable)
* **Present_Price** – Current showroom price of the car
* **Driven_kms** – Total kilometers driven
* **Fuel_Type** – Type of fuel used (Petrol, Diesel, CNG)
* **Selling_type** – Dealer or Individual seller
* **Transmission** – Manual or Automatic transmission
* **Owner** – Number of previous owners

## Steps Performed

1. Imported necessary Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.
2. Loaded the car dataset.
3. Checked dataset information and missing values.
4. Removed unnecessary columns.
5. Converted categorical variables into numerical values.
6. Split the dataset into training and testing sets.
7. Trained a Linear Regression model for price prediction.
8. Evaluated the model using Mean Squared Error.

## Model Used

Linear Regression

## Evaluation Metric

Mean Squared Error (MSE)

## Visualization

A scatter plot was created to compare **actual car prices vs predicted car prices**, showing how well the model predictions match the real values.

## Result

The model was able to predict the selling price of used cars with a Mean Squared Error of approximately **3.53**, indicating reasonable prediction performance.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Conclusion

This project demonstrates how machine learning techniques can be applied to predict used car prices based on several features. The Linear Regression model was able to capture the relationship between car attributes and their selling prices, providing useful insights for price estimation.

