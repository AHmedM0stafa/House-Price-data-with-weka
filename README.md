# House-Price-data-with-weka
Ml models on House Price dataset with weka data Mining App.

## Dataset Description


The "[House Price India]([url](https://www.kaggle.com/datasets/mohamedafsal007/house-price-dataset-of-india/code?select=House+Price+India.csv))" dataset is a collection of data on house prices in India. The dataset includes information on various features of the houses, such as the number of bedrooms, bathrooms, living area, lot area, and whether or not the house has a waterfront view. The data was collected and uploaded to Kaggle by a user named Mohamed Afsal.
The dataset is in CSV format and includes 9 columns and 1,460 rows. The columns are as follows:
    1. Id: A unique identifier for each house listing
    2. Date: The date on which the house was listed for sale
    3. Bedrooms: The number of bedrooms in the house
    4. Bathrooms: The number of bathrooms in the house
    5. Living Area: The area of the living space in square feet
    6. Lot Area: The area of the lot in square feet
    7. Water Front Present: A binary indicator (0 or 1) that indicates whether the house has a waterfront view
    8. Price: The price of the house in Indian Rupees (INR)
    9. Location: The location of the house in India
    
    
 ### To solve this problem using Weka, we will follow the following steps:
 
  1. Data Preprocessing: We will preprocess the "House Price India" dataset using various filters in Weka such as handling missing values, data normalization, data discretization, feature selection, data transformation, and handling categorical attributes.
  
  2. Model Selection: We will train and evaluate different regression models in Weka such as Linear Regression, Decision Tree, Random Forest, and Support Vector Machine. We will choose the best-performing model based on evaluation metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R^2).



### Data preprocessing steps:

Here are some data preprocessing steps that can be performed on the "House Price India" dataset using Weka:
  
  1-Handling missing values: The dataset may contain missing values, which can be handled by replacing them with suitable values    such as the mean or median of the column, or by removing the rows or columns with missing values altogether. In Weka, you can     use the "ReplaceMissingValues" filter to replace missing values with the mean or median of the column


  2-select important feature


### Model Selection steps:
  The algorithms that we will review are:
  
    - Random Forest
    - Linear Regression
    - Decision Tree
    - Support Vector Machines



The objective of applying the mining task to this dataset is to develop an accurate model to predict house prices in India. This model should be able to identify the most important 
factors that influence house prices and provide accurate predictions for new instances.



