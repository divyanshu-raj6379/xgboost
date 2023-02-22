# xgboost
The XGBoost project lies on a Jupyter Notebook which starts with the derivation of the Objective function for XGBoost CART algorithm. \
The algorithm is then implementation on a Weather dataset whcih predicts the possibility of Rain on a given day. \
The dataset is an imbalanced dataset with occurance of Rain being the positive outcome, and no rain as the negative outcome. \
In order to overcome the challenge of imbalanced dataset, Class-weighted XGBoost algorithm is implemented by calculating the required hyperparameter. \
Null values in the dataset are imputed using an Itearative Imputer. \
The Base XGBoost model was able to correctly predict the Positive outcome at only 48%. \
After tuning the hyper-parameters, the model performance improved and TPR value increased to about 78%.
