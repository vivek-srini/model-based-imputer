Hi! This repository has a model-based imputer which takes a dataframe with missing values and fills the missing values. How does it do it?

1. If the feature is categorical, it uses logistic Regression as a model - it uses the feature to be imputed as a target and every other feature as input
2. 1. If the feature is numeric, it uses linear Regression as a model - it uses the feature to be imputed as a target and every other feature as input
