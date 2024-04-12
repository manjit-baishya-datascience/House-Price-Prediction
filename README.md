# **House Price Trend Analysis and Price Prediction**
![Asset 13](https://github.com/manjit-baishya-datascience/House-Price-Prediction/assets/127611924/2991fd55-d861-4e6d-9a40-726656b33dd6)

## **Contents**
1. [**Author**](#author)
2. [**Aim**](#aim)
3. [**Statement of Work**](#statement-of-work)
   1. [**Overview**](#overview)
   2. [**Objectives**](#objectives)
   3. [**Timeline and Milestones**](#timeline-and-milestones)
4. [**About the Dataset**](#about-the-dataset)
   1. [**List of Columns**](#list-of-columns)
5. [**Importing Data**](#importing-data)
6. [**Data Cleaning**](#data-cleaning)
7. [**Exploratory Data Analysis**](#exploratory-data-analysis)
8. [**Machine Learning**](#machine-learning)

## **Statement of Work**

1. Import and load the dataset from a specified source location.
2. Clean and preprocess the data to remove duplicates, handle missing values, and transform the dataset for analysis.
3. Conduct exploratory data analysis **(EDA)** to gain insights into house price trends and distributions.
4. Implement machine learning models to predict house prices based on property attributes.
5. Evaluate and compare the performance of different regression algorithms to identify the best-performing model for house price prediction.

## **About the Dataset**

The dataset contains the following columns:

- `type`: Type of property (e.g., Flat, House)
- `locality`: Location or locality of the property
- `city`: City where the property is located
- `baths`: Number of bathrooms in the property
- `beds`: Number of bedrooms in the property
- `purpose`: Purpose of the property listing (e.g., For Sale, For Rent)
- `area`: Area of the property in square feet
- `price`: Price of the property

## **Importing Data**

This project involves analyzing house price trends and making predictions using machine learning. The dataset is imported from a specified source location and loaded into a pandas DataFrame for further analysis. Essential libraries such as `numy`, `pandas`, `seaborn`, and `matplotlib` are imported to facilitate data manipulation and visualization tasks, which are essential for exploring and understanding the dataset's structure and contents effectively.

## **Data Cleaning**

The data cleaning process ensures that the dataset is well-prepared for analysis and modeling. Key tasks include:

1. **<u>Removing Unnecessary Columns:</u>** <br>The `Unnamed: 0` column, likely representing an index, is dropped as it does not contribute to the analysis.

2. **<u>Handling Missing Values:</u>** <br>Checking for missing values (`NaN`) in the dataset confirms that no columns have missing data, ensuring data completeness.

3. **<u>Removing Duplicates:</u>** <br>Duplicate records are identified and removed to avoid bias and inaccuracies in subsequent analyses.

4. **<u>Column Renaming:</u>**<br> Columns are renamed for clarity (`type` instead of `property_type`, `locality` instead of `location`) to enhance readability and understanding of the dataset.

5. **<u>Data Transformation:</u>**<br> Converting property area from Marla to Square Feet (`marla` to `area`) ensures consistency in units for standardized analysis.

## **Exploratory Data Analysis**

Exploratory Data Analysis (EDA) provides valuable insights into the dataset:

1. **<u>Statistical Overview:</u>** Descriptive statistics (mean, median, quartiles) reveal the distribution and range of numerical features like baths, beds, area, and price.

2. **<u>Visualization:</u>** Count plots and bar charts are utilized to visualize the distribution of property types, cities, and average prices across different localities. These visualizations aid in identifying trends and patterns within the dataset.

3. **<u>Key Insights:</u>** Analysis highlights the average price of properties, distribution of property types, and significant variations in property prices across different localities and cities.

## **Machine Learning**

The machine learning phase involves building predictive models using various regression algorithms:

1. **<u>Data Preprocessing:</u>** Categorical variables (`type`, `city`, `locality`, `purpose`) are encoded using one-hot encoding to convert them into numerical format suitable for modeling.
2. **<u>Model Training and Evaluation:</u>** The dataset is split into training and testing sets. Multiple regression models - `Linear Regression`, `Ridge Regression`, `Lasso Regression`, `Elastic Net Regression`, `Decision Tree Regressor`, `Random Forest Regressor`, `Gradient Boosting Regressor`, `KNN Regressor` are trained on the training set and evaluated using metrics like `RMSE` and `R-squared` to assess prediction accuracy.
3. **<u>Model Comparison:</u>** The performance of each model is compared based on evaluation metrics to identify the best-performing model for predicting house prices.

# **Conclusion**
In conclusion, the analysis presented in this project sheds light on various aspects of house price trends and prediction using machine learning. Through thorough data cleaning, exploratory data analysis, and machine learning modeling, we have gained valuable insights into the dataset's structure and patterns. The findings from statistical overviews and visualizations have highlighted key trends in property types, city-wise distributions, and average prices across different localities. Moreover, the evaluation of multiple regression models has provided a comparative analysis of their performance in predicting house prices. Moving forward, the results can be utilized to inform real estate decisions, pricing strategies, and market insights based on a comprehensive understanding of the dataset.

# **THANK YOU**
