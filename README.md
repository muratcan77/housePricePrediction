# housePricePrediction

House Price Prediction Project
Welcome to the House Price Prediction project! This project focuses on predicting the final prices of residential homes in Ames, Iowa, based on a dataset with 79 explanatory variables covering almost every aspect of these homes. The dataset was compiled by Dean De Cock for data science education, providing a rich playground for practicing creative feature engineering and advanced regression techniques.

Project Overview
Data Exploration and Cleaning
The project starts with a thorough exploration of the dataset, checking for missing values, outliers, and data types. Various functions, such as check_df and grab_col_names, help gain insights into the data's structure.

Preprocessing
Several preprocessing steps are applied, including handling missing values, rare encoding, and creating new features to enhance the predictive power of the models. The dataset undergoes label encoding and one-hot encoding to prepare categorical variables for modeling.

Feature Engineering
The project introduces new features like NEW_1st*GrLiv, NEW_TotalFlrSF, NEW_PorchArea, and many more, derived from creative combinations of existing variables to capture essential information about the houses.

Modeling
The predictive models used in this project include Linear Regression, K-Nearest Neighbors, Random Forest, and XGBoost. Cross-validation is employed to evaluate the models, and the Root-Mean-Squared-Error (RMSE) is utilized as the evaluation metric.

Results
The results and performance metrics of each model are displayed, providing a comprehensive overview of their effectiveness in predicting house prices.

Acknowledgments
Special thanks to Dean De Cock for compiling the Ames Housing dataset, which serves as the foundation for this project and supports data science education.

