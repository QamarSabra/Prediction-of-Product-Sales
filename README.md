# Prediction of Product Sales 💼📊 💼✨
 
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
![heatmap](https://github.com/user-attachments/assets/3f6cf796-8d7c-472f-bc41-b44ce2710c9c)

This heatmap shows the correlation between different features in the dataset. It highlights that **Item MRP** has the strongest positive correlation with **Item Outlet Sales**, making it a key factor in predicting sales.
---
 
## What You’ll Find in This Project 📑
 
- **Load and Inspect Data**: Loading the dataset and performing an initial inspection of the data. 🔍
- **Clean Data**: Handling missing values, correcting data types, and ensuring the dataset is ready for analysis. 🧼✨
- **Exploratory Data Analysis (EDA)**: Visualizing and summarizing the data to uncover key patterns and trends. 📊🔍
- **Feature Inspection**: Examining the features and understanding their role in predicting the target variable. 🛠️👀
