# 🏠 House Price Prediction

## 📈 Overview

House Price Prediction using Machine Learning. Today, we will be preparing a MACHINE LEARNING Based model, trained on the House Price Prediction Dataset.

## 📊 Dataset Features

The dataset contains 13 features:

- **Id**: To count the records.
- **MSSubClass**: Identifies the type of dwelling involved in the sale.
- **MSZoning**: Identifies the general zoning classification of the sale.
- **LotArea**: Lot size in square feet.
- **LotConfig**: Configuration of the lot.
- **BldgType**: Type of dwelling.
- **OverallCond**: Rates the overall condition of the house.
- **YearBuilt**: Original construction year.
- **YearRemodAdd**: Remodel date (same as construction date if no remodeling or additions).
- **Exterior1st**: Exterior covering on house.
- **BsmtFinSF2**: Type 2 finished square feet.
- **TotalBsmtSF**: Total square feet of basement area.
- **SalePrice**: To be predicted.

## 🧹 Data Cleaning

Data Cleaning is essential to improve data quality. This involves:

- Dropping irrelevant columns like the 'Id' column.
- Handling empty/null values by either deleting them or filling them with appropriate values.

## 🛠️ Data Transformation

One hot Encoding is utilized to convert categorical data into binary vectors. This involves mapping values to integer values.

## 📊 Data Analysis

Categorical features are analyzed using barplots to visualize unique categories and their counts.

## 📉 Model and Accuracy

Regression models are used for predicting continuous values:

- **SVM-Support Vector Machine**
- **Random Forest Regressor**
- **Linear Regressor**

Training and testing datasets are split into X and Y, where Y represents the SalePrice column, and the remaining columns are X.

