# Food Delivery Time Prediction
A machine learning project that analyzes food delivery data and develops predictive models to estimate delivery time based on factors such as delivery distance, traffic conditions, weather, vehicle type, and delivery personnel characteristics.
**Python · Google Colab · Machine Learning · Scikit-learn**

## 1. Project Overview

Accurately estimating food delivery time is important for improving customer satisfaction and optimizing delivery operations. However, delivery time can be influenced by several factors, including traffic congestion, weather conditions, distance, and vehicle condition.

This project aims to develop a machine learning-based solution to predict food delivery time (in minutes) using historical delivery data.

The project explores the relationship between delivery-related features and delivery duration through data preprocessing, exploratory data analysis, feature engineering, and predictive modelling.

## 2. Objectives

-Analyze the factors influencing food delivery time.
-Perform data cleaning, preprocessing, and exploratory data analysis.
-Engineer meaningful features, including geographical delivery distance and order-time attributes.
-Develop and compare machine learning models for delivery time prediction.
-Evaluate model performance using appropriate regression metrics.

## 3. Dataset

The project uses a food delivery dataset containing information about orders, delivery personnel, restaurants, delivery locations, weather, traffic, and delivery duration.

_Dataset source: Kaggle – Food Delivery Dataset_

## 4. Technologies and Libraries

Python, Google Colab, Pandas, Numpy, Matplotlib, Seaborn, Scikit learn

## 5. Project Workflow

The project follows a structured machine learning workflow:

**Data Collection**: Load and inspect the food delivery dataset.
**Data Cleaning**: Handle missing values, duplicates, inconsistent formats, and invalid records.
**Exploratory Data Analysis (EDA)**: Investigate delivery-time distributions and relationships between features.
**Feature Engineering**: Calculate geographical distance using the Haversine formula and extract useful time-based features.
**Data Preparation**: Separate features and target variables, split the dataset into training and testing sets, and build preprocessing pipelines.
**Model Development**: Train and compare suitable machine learning regression models.
**Model Evaluation**: Assess predictive performance using regression evaluation metrics.

## 6. Feature Engineering and Preprocessing

Some of the key preprocessing techniques implemented include:

-Conversion of categorical and numerical data into appropriate formats.
-Handling missing values using median and most-frequent imputation.
-Encoding ordinal features using OrdinalEncoder.
-Encoding nominal features using OneHotEncoder.
-Feature scaling using StandardScaler for Linear Regression.
-Calculation of restaurant-to-delivery distance using the Haversine formula.
-Extraction of order hour, day of the week, and weekend indicators.
-Separate preprocessing pipelines are developed for Decision Tree and Linear Regression models.

## 7. Results and Visualizations

Planned visualizations include:

-Distribution of delivery times.
-Delivery time across different traffic conditions.
-Impact of weather and vehicle type on delivery duration.
-Correlation heatmap of numerical features.
-Comparison of actual and predicted delivery times.

Model performance will be reported using appropriate regression metrics such as:

-Mean Absolute Error (MAE)
-Mean Squared Error (MSE)
-Root Mean Squared Error (RMSE)
-R² Score

## 8. Author

Anamika J
-GitHub: github.com/Anamika79
-LinkedIn: linkedin.com/in/anamika-j

_This project is developed as part of a hands-on exploration of machine learning, data analysis, and predictive modelling._
