# Prediction-of-Product-Sales
- The objective of this project is to predict sales for food items sold at various stores by helping the retailer understand the properties of products and outlets that play crucial roles in increasing sales.
- Original Data:
[Link](https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view)
- Below are two sample images from the type of visuals and plots I show throughout the project.
![item_type_fat_barplot](https://github.com/parkerholds/Prediction-of-Product-Sales/assets/140461361/2b31d106-90d1-4ebf-a126-8c23d4c30f2b)
![item_mrp_boxplot](https://github.com/parkerholds/Prediction-of-Product-Sales/assets/140461361/8ceaf7c9-58e0-460d-bf0a-5e3ce3eb47c4)

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

## Random Forest Metrics: Training Data:
- MAE = 653.282
- MSE = 868,038.260
- RMSE = 931.686
- R^2 = 0.707

## Random Forest Metrics: Test Data:
- MAE = 734.396
- MSE = 1,118,366.971
- RMSE = 1,057.529
- R^2 = 0.595
