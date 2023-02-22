# xgboost
The XGBoost project lies on a Jupyter Notebook which starts with the derivation of the Objective function for XGBoost algorithm. \
The algorithm is then implemented on a Weather dataset which predicts the possibility of Rain on a given day. \
The dataset is an imbalanced dataset with occurance of Rain being the positive outcome, and no rain as the negative outcome. \
The positive outcome data constitutes only 22% of the entire data. \
In order to overcome the challenge of imbalanced dataset, Class-weighted XGBoost algorithm is implemented by calculating the required hyperparameter. \
Null values in the dataset are imputed using an Itearative Imputer. \
The Base XGBoost model was able to correctly predict the Positive outcome at only 46%. \
After tuning the hyper-parameters, the model performance improved and TPR value increased to about 79%.
