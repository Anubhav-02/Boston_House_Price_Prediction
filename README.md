# Boston Housing Price Prediction
The project predicts house prices using a dataset based on Boston Houses.

# Data Exploration and Preprocessing:
   -  Visualized data distributions and identified potential outliers.
   -  Performed min-max normalization to scale features.
   -  Analyzed correlations between features and the target variable (*medv*)

# Feature Selection:
   -  Identified '*lstat*' and '*rm*' as strong predictors of '*medv*' based on regression plots.
   -  Removed '*rad*' as it did not seem to contribute significantly to the model.

# Model Training and Evaluation:
   -  Trained various regression models (Linear Regression, Decision Tree, Random Forest, Extra Trees, XGBoost).
   -  Evaluated models using Mean Squared Error (MSE), Cross-Validation Score, and Accuracy (R-squared).

# Key Performance Metrics:
   -  XGBoost exhibited the best performance with a high accuracy(*83%*) and low MSE.
   -  Other models also showed good performance, with Random Forest(*82%*) and Extra Trees(*79*) having comparable results.

# Overall:
   - The analysis demonstrates the importance of feature selection and model selection for optimal prediction.
   - XGBoost emerged as the top-performing model for this dataset.
