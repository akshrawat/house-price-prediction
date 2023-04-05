# house-price-prediction

# Dataset Information

This dataset is from a Kaggle competition. It contains train, test and data description file.

It contains 80 features and total of 2919 data.

# Libraries

 - numpy
 - pandas
 - matplotlib
 - sklearn
 - seaborn
 - scipy
 - pycaret
 
 # Algorithms
 
  I used pycaret library which runs all models and gives us a comparision. Then I took top 5 models for our predictions.
  
    - Catboost
    - BayesianRidge
    - LGBM Regressor
    - Ridge Regressor
    - OrthogonalMatchingPursuit
    
  Used Kfold cross validation for scores. The best score was acquired by combining all above algorithms with some weights.
