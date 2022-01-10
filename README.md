# kidney_disease_practice
### Predict Chronic Kidney Disease

*Dataset used from Kaggle: https://www.kaggle.com/mansoordaku/ckdisease*

Perfomed data cleaning and preprocessing, EDA, feature importance, PCA and prediction using 5 models: Decision Tree, Random Forest, Griv Search, XgBoost and TabNet.

In this notebook:

- analyzed Chronic Kidney Disease dataset

- performed EDA

- tried out Principal Component Analysis (PCA)

- used different models for prediction: Decision Tree, Grid Search, Random Forest, XgBoost, TabNet (with Optuna optimization)

- used different packages for feature importance analysis: LIME, SHAP, Boruta

In conclusion, Decision Trees and TabNet perform well with optimization (in our case GridSearch/Optuna), whereas XgBoost is capable of outperforming them singlehandedly. TabNet is proven itself to work good with tabular data, which is common among classic neural network models, but still, tree models and boosting are more effiecient in this case - even though they are easier to implement due to their simplicity, they can maintain high performance with data like used here. When analyzing feature importance we can see, that important features are the same which are considered to be main causes of CKD.
