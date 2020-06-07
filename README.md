# CorrelationKC
Correlation on Kansas City Data

Team: Gauntlet
(Shiva Kumar Murarishetti,
Jagruthi Bobbala)


Data has divided into Train(80%), Test(20%).
Data is classified into Numerical, categorical.
Filtered Data based on correlation values >0.3 and <-0.3.
No Null values found in data, so we didn’t use mean, median or mode to fill the NULL values.
Implemented Prediction on:
  Black Persons In Poverty
  Households With Income Less Than $10,000
  Minority


We have used :
  Corr()-correlation,
  LabelEncoder,
  le.fit_transform,
  LinearRegression,
  train_test_split,
  DecisionTreeRegressor,
  RandomForestRegressor,
  GradientBoostingRegressor,
  accuracy_score,
  r2_score
