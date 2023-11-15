# Prediction-of-Product-Sales
- The objective of this project is to predict sales for food items sold at various stores by helping the retailer understand the properties of products and outlets that play crucial roles in increasing sales.
- Original Data:
[Link](https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view)
- Below are two sample images from the type of visuals and plots I show throughout the project.
![item_mrp_boxplot](https://github.com/parkerholds/Prediction-of-Product-Sales/assets/140461361/8ceaf7c9-58e0-460d-bf0a-5e3ce3eb47c4)
 
 - Starchy foods has the highest median value for Item_MRP
 - Dairy category has the highest 3rd quartile values. Implying high volatility. 
 - Baking goods has the lowest median value.
 - Health and Hygiene has the highest single outlier.
![countplotitemssold](https://github.com/parkerholds/Prediction-of-Product-Sales/assets/140461361/9f1fed5d-d534-404d-9a30-b217b894d2e8)
 - This is an important barplot showing us which items have the most outlet sales.
 - Fruits and Vegetables have the most amount of items sold. Snack Foods are close behind with the 2nd most.
 - Breakfast and Seafood have the least amount sold.


## Data Cleaning
- Addressed any duplicate rows
- Fixed categorical inconsistencies
- Imputed any missing values with appropriate methods.

## Models created
- Linear Regression
- Default Random Forest
- Tuned Random Forest

## Linear Regression Metrics: Training Data:
- MAE = 847.111
- MSE = 1,297,579.298
- RMSE = 1,139.113
- R^2 = 0.562

## Linear Regression Metrics: Test Data:
- MAE = 804.026
- MSE = 1,194,197.603
- RMSE = 1,092.793
- R^2 = 0.567

## Tuned Random Forest Metrics: Training Data:
- MAE = 653.282
- MSE = 868,038.260
- RMSE = 931.686
- R^2 = 0.707

## Tuned Random Forest Metrics: Test Data:
- MAE = 734.396
- MSE = 1,118,366.971
- RMSE = 1,057.529
- R^2 = 0.595

### Overall I recommend the tuned Random Forest model. It gives us our most realistic R^2 score and with further tuning I believe we can dial in the bias and variance better.
 - The R^2 score also called the "coefficient of determination" basically describes the percentage of variation in the target (price) that a model can explain. A higher R^2 socre is better, where 1 means perfect fit on the data.
 - Another metric to look at is RMSE. This is the Root mean squared error and it rewards a model that is mroe consistent and punishes large errors. It is easy to interpert. In this case our target is price so we'll look at in dollars. Our RMSE in this case is $1,057.
