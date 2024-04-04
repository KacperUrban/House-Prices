# House-Prices
## General Info
The project objective was prediction of the house prices. The data which i used are from Kaggle competition House Prices - Advanced Regression Techniques. My project I divided on four parts. First was about loading data, take a peek on data and remove missing values.
EDA
In the next step I conducted a EDA. In Explanatory Data Analysis i conducted univariate, bivariate and multivariate analysis. I checked the correlation, mutual information and did some visualizations.
### Feature Engineering
In that step I encoded a categorical columns with ordinal and one-hot encoder. I created a new columns and also used a box-cox transformation. On the end I created a transformation pipeline.
### Model training
I used a few models. For example:
- Linear Regression
- Elastic Net Regression
- Support Vector Machines regression
- XGBoost regression
- LightGBM regression
I checked models accuracy with cross-validation. I used a root mean squared error as a metric. Every model was checked on preprocess data and preprocess data additionaly with PCA.
### Hyperparameter tunning
I choose two bests models and conducted a hyperparameter tunning with hyperopt. I used a bayesian optimization algorithm a Tree-Structed Parzen Estimator.
## Technologies
The project is created with:
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Xgboost
- Lightgbm
- Hyperopt
## Status
The project is ongoing.

