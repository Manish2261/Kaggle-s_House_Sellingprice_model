# Kaggle-s_House_Sellingprice_model
It is an advanced regression model which predicts the selling prices of the houses..


## Intro to Model:- 
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home. The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset.

## Metric of Evaluation :-
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

## The Approach for Evaluation:-

As the number of features in the datasets where in very handsome numbers, therefore as a basic approach by checking the information relating to
variable from the imported datasets.

### Step: 1st: Looking for minimal Changed variable.
As after looking for some area to start the data exploration, I noticed that, there were certain categorical variable whcih were having a very 
little or no change in their values of category. And so, I first tried to eliminate them as they are were minimally going to affect the results 

### Step 2nd: Eliminating those Categorical variable
As per my observation, in order to reduce the complexity of encoding the datasets and also to reduce te computational period, I decided to eiminate such variable on a hole and sole purpose. They were as follows:
Street,
Alley,
LotShape,
LandContour,
Utilities,
LotConfig
Exterior1st,
Exterior2nd,
MasVnrType,
Electrical,
BsmtExposure,
BsmtFinType1,
BsmtFinType2,
BsmtFinSF1,
BsmtFinSF2
HeatingQC,
Heating,
Functional,
PoolQC,
Fence,
MiscFeature,
MSZoning,
KitchenQual,
SaleType.
These variable were completely eliminated bringing the new training set size upto 50 Variable.


