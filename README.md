# Prediction of Product Sales 💼📊✨
 
## Project Overview
 
Welcome to my portfolio project! This project demonstrates my data science skills through the exploration and analysis of a sales dataset. You'll find a step-by-step breakdown of the entire process, from loading and cleaning the data to performing in-depth analysis. Let’s dive in!
 
---
 
### 📋 Feature Dictionary
 
| Feature                      | Description                                                                                                       | Example      |
|------------------------------|-------------------------------------------------------------------------------------------------------------------|--------------|
| `Item_Identifier`             | Unique product ID                                                                                                | FDA15        |
| `Item_Weight`                 | Weight of the product in kilograms                                                                                | 9.30         |
| `Item_Fat_Content`            | Whether the product is Low Fat or Regular                                                                         | Low Fat      |
| `Item_Visibility`             | The percentage of the product’s visibility in the store                                                           | 0.016047     |
| `Item_Type`                   | The category of the product (e.g., Dairy, Soft Drinks, Household)                                                 | Dairy        |
| `Item_MRP`                    | Maximum Retail Price (MRP) of the product in local currency                                                       | 249.8092     |
| `Outlet_Identifier`           | Unique store ID                                                                                                  | OUT049       |
| `Outlet_Establishment_Year`   | The year the store was established                                                                                | 1999         |
| `Outlet_Size`                 | Size of the store (Small, Medium, High)                                                                           | Medium       |
| `Outlet_Location_Type`        | The location type of the store (Tier 1, Tier 2, Tier 3)                                                           | Tier 1       |
| `Outlet_Type`                 | Type of store (e.g., Grocery Store, Supermarket Type1)                                                            | Supermarket Type1 |
| **`Item_Outlet_Sales`**       | **Total sales of the product in that particular store (Target variable)**                                         | 3735.1380    |
 
---
 
## Key Insights 🔍
 
### Feature Correlation Heatmap 🔥
 
![Heatmap](https://github.com/user-attachments/assets/bf10bb6b-f6ad-4543-9ba8-cae1fdc87b05)
 
This heatmap shows the correlation between different features in the dataset. It highlights that **Item MRP** has the strongest positive correlation with **Item Outlet Sales**, making it a key factor in predicting sales.
 
### Linear Regression Coefficients 📈
 
![co](https://github.com/user-attachments/assets/9c7bc729-b7e7-4b99-9fd5-d474a5910318)
 
The bar chart above displays the top coefficients from the linear regression model. **Outlet_Type_Supermarket Type3** and Item MRP have the largest positive coefficients, indicating they are the most influential in predicting sales.
 
### Random Forest Feature Importance 🌲
 
![im](https://github.com/user-attachments/assets/e6a817af-855c-44c6-809e-b6b638e47524)
 
The feature importance plot from the Random Forest model shows **Item MRP** and **Outlet_Type** as the most important predictors of sales, with **Outlet_Establishment_Year** having minimal impact compared to other features.
 
### Model Performance Metrics 📊
 
The table below summarizes the performance of Linear Regression and Random Forest models on both training and test datasets.
 
| Model               | Dataset       | MAE     | MSE         | RMSE     | R²    |
|---------------------|---------------|---------|-------------|----------|-------|
| **Linear Regression** | Training Data | 848.362 | 1,299,195.297 | 1139.822 | 0.561 |
|                     | Test Data     | 806.114 | 1,197,186.399 | 1094.160 | 0.566 |
| **Random Forest**   | Training Data | 755.688 | 1,134,219.997 | 1064.998 | 0.617 |
|                     | Test Data     | 733.514 | 1,102,325.082 | 1049.917 | 0.600 |
 
**Interpretation**: The Random Forest model outperforms Linear Regression in terms of lower MAE, MSE, and RMSE, as well as a higher R² score, indicating a better fit for predicting sales in this dataset.
 
---
 
## What You’ll Find in This Project 📑
 
- **Load and Inspect Data**: Loading the dataset and performing an initial inspection of the data. 🔍
- **Clean Data**: Handling missing values, correcting data types, and ensuring the dataset is ready for analysis. 🧼✨
- **Exploratory Data Analysis (EDA)**: Visualizing and summarizing the data to uncover key patterns and trends. 📊
- **Feature Inspection**: Examining the features and understanding their role in predicting the target variable. 🛠️👀
- **Modeling and Evaluation:** Building and evaluating Linear Regression and Random Forest models, with fine-tuning for optimal performance. 🔧📈
