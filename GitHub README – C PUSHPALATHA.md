# Car Market Trends Analysis Using CarDekho Data

## Project Overview

This project analyzes used-car data from CarDekho to understand the factors that influence the selling price of cars.

The analysis focuses on factors such as present price, car age, kilometers driven, fuel type, seller type, transmission, and number of previous owners.

## Student Details

**Name:** C PUSHPALATHA  
**AICTE ID:** STU696132c929d891767977673  
**College:** Justice Basheer Ahmed Sayeed College for Women

## Objectives

- Analyze used-car selling prices.
- Study the relationship between present price and selling price.
- Understand the effect of car age on resale price.
- Analyze the impact of kilometers driven.
- Compare cars based on fuel type, seller type, and transmission.
- Study the effect of previous ownership.
- Identify car models with higher and lower average selling prices.
- Build machine learning models to predict selling prices.

## Dataset

The dataset contains **301 used-car records** with the following attributes:

- Car_Name
- Year
- Selling_Price
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Google Colab
- GitHub

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Price Analysis
6. Car Age Analysis
7. Kilometers Driven Analysis
8. Fuel Type Analysis
9. Seller Type Analysis
10. Transmission Analysis
11. Ownership Analysis
12. Correlation Analysis
13. Outlier Analysis
14. Machine Learning
15. Results and Insights

## Feature Engineering

The project creates additional features such as:

- **Car Age** – calculated using the reference year 2020.
- **Depreciation** – difference between present price and selling price.
- **Depreciation Percentage** – percentage decrease from present price.
- **Kms Category** – groups cars based on kilometers driven.
- **Owner Label** – converts owner codes into meaningful ownership categories.

## Machine Learning

Two machine learning models are used:

### Linear Regression

Linear Regression is used to understand and predict the relationship between the selected car features and selling price.

### Random Forest Regression

Random Forest Regression is used as a second model for predicting the selling price and comparing its performance with Linear Regression.

The models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Key Insights

- Present price is an important factor affecting selling price.
- Car age has a noticeable relationship with resale value.
- Higher kilometers driven generally influence the selling price.
- Petrol cars form the majority of the dataset.
- Manual transmission cars are more common than automatic cars.
- Dealer listings are more common than individual listings.
- Different car models show significant differences in average selling price.

## Conclusion

The project provides an overview of used-car market trends using data analysis and machine learning.

The findings can help buyers, sellers, dealers, and automobile businesses understand important pricing factors and make better decisions in the used-car market.

## Project Files

- `Car_Market_Trends_Analysis_C_Pushpalatha.ipynb`
- `CarDekho Dataset.csv`
- `README.md`

## Author

**C PUSHPALATHA**  
Justice Basheer Ahmed Sayeed College for Women