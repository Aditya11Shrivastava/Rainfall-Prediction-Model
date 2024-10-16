# Rainfall Prediction Model

# Dataset
The dataset used in this project consists of approximately 1.42 lakh records with meteorological data to predict whether it will rain tomorrow.

# Model Evaluation
• Various machine learning models were tested and evaluated for performance, including:

• Logistic Regression: 86% accuracy

• Decision Tree: 88% accuracy

• Neural Network: 94% accuracy

• Random Forest: 97% accuracy

• LightGBM: 93% accuracy

• CatBoost: 97.5% accuracy

• XGBoost: 98% accuracy

# Evaluation Metrics
• Accuracy: The primary metric to assess the models' performance in predicting rainfall.

• ROC AUC (Area Under Curve): To evaluate the probability scores output by models and their ability to distinguish between classes.

• Cohen’s Kappa: Used to measure the agreement between predicted and actual values, especially when dealing with imbalanced data.

• Execution Time: The time taken for training and prediction was recorded for each model.

# Handling Imbalanced Data
• Since the dataset was highly imbalanced (78% of instances labelled as "No Rain"), oversampling was performed to balance the data for better model training.

# Model Comparison
• A detailed comparison was made using accuracy and time taken by each model. The best-performing models were XGBoost and CatBoost based on a balance of accuracy and execution time.
• However, if speed is an important thing to consider, we can stick with Random Forest instead of XGBoost or CatBoost.
