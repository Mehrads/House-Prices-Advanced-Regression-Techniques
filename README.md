# House-Prices-Advanced-Regression-Techniques
# 1. Problem definition
#### What problem are we trying to solve?
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges us to predict **the final price of each home**.

**Goal**: It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 


# 2. Data
#### What data do we have?
Here's a brief version of what you'll find in the data description file.

There are 1460 instances of training data and 1460 of test data. The total number of attributes equals 81, of which 36 are quantitative, 43 categorical + Id and SalePrice. <br>

Quantitative: 1stFlrSF, 2ndFlrSF, 3SsnPorch, BedroomAbvGr, BsmtFinSF1, BsmtFinSF2, BsmtFullBath, BsmtHalfBath, BsmtUnfSF, EnclosedPorch, Fireplaces, FullBath, GarageArea, GarageCars, GarageYrBlt, GrLivArea, HalfBath, KitchenAbvGr, LotArea, LotFrontage, LowQualFinSF, MSSubClass, MasVnrArea, MiscVal, MoSold, OpenPorchSF, OverallCond, OverallQual, PoolArea, ScreenPorch, TotRmsAbvGrd, TotalBsmtSF, WoodDeckSF, YearBuilt, YearRemodAdd, YrSold <br>

Qualitative: Alley, BldgType, BsmtCond, BsmtExposure, BsmtFinType1, BsmtFinType2, BsmtQual, CentralAir, Condition1, Condition2, Electrical, ExterCond, ExterQual, Exterior1st, Exterior2nd, Fence, FireplaceQu, Foundation, Functional, GarageCond, GarageFinish, GarageQual, GarageType, Heating, HeatingQC, HouseStyle, KitchenQual, LandContour, LandSlope, LotConfig, LotShape, MSZoning, MasVnrType, MiscFeature, Neighborhood, PavedDrive, PoolQC, RoofMatl, RoofStyle, SaleCondition, SaleType, Street, Utilities, <br>

# 3. Evaluation
#### What defines success?
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

# Final Result 
![Final Result picture](https://github.com/Mehrads/House-Prices-Advanced-Regression-Techniques/blob/main/Screenshot%201402-05-31%20at%2018.16.23.png)
