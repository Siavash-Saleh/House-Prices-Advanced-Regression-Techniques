# House Price Prediction – Kaggle Project
# Question: Ever wondered how much a house should cost based on its features?
In this project, I worked on predicting house prices using the Kaggle House Prices dataset. Here’s a quick overview of what I did:

🔹 Data Loading
Loaded both the training and test datasets to start exploring the data and building the model.

🔹 Preprocessing
Filled missing values: used the mean for numerical columns and mode for categorical ones.

Separated numerical and categorical features to make the pipeline cleaner.

Explored feature correlations and visualized outliers, but kept all data intact — no removals.

Checked the distribution of numerical features to get a sense of their range and skew.

🔹 Data Integrity
Kept all original features and outliers without using any information from the test set.

This helped prevent data leakage and kept the modeling process honest.

🔹 Train/Test Split
Split the training data for validation so I could test how well the model generalizes before making final predictions.

🔹 Model Selection
I chose CatBoost for this task because it works really well with categorical data and requires minimal preprocessing.

🔹 Tuning & Validation
Tuned the model using GridSearchCV.

Applied 5-fold cross-validation to catch overfitting and make the model more robust.

🔹 Prediction
Generated predictions on the test set.

Merged the predictions with the test DataFrame and prepared the submission file.

