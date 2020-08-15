# HotelCancel
Predicting Hotel Cancellations Using Random Forest (Bagging) and Optuna

Dataset from Kaggle: https://www.kaggle.com/jessemostipak/hotel-booking-demand

Proccess:
- Used various techniques to impute missing values.
- Used various techniques to encode the categorical variable (Label encoding, one-hot, target-guided encoding etc.)
- Correlated features removed and computed feature importance
- Comparing different models --> Baseline Logistic regression vs Random Forests
- Automated hyperparameter tuning using optuna

Results:
- We are able to predict Hotel Cancellation, with a high degree of accuracy (89% both cross-validation set and Test set)
 
