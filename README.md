# BALCO-T4-Alloy-Project
# PRoJECT OVERVIEW
It’s a project that focuses on predicting multiple target variables using multioutput regression. The project utilizes a dataset called RUL_database, which is loaded from a CSV file containing various parameters related to wire rod production.

The main objective of the project is to predict the values of multiple target variables simultaneously based on the given input features. The target variables represent different aspects of wire rod production, such as Cast Bar Temperature, Casting Water Temperature, Emulsion Temperature, RAC Water Temperature, Casting Water Flow, Emulsion Pressure Flow, Gear Oil Pressure, Gear Oil Temperature, Casting Pressure, RAC Pressure, and Tundish Temperature whereas the features are ultimate tensile strength and conductivity.
![image](https://github.com/rishi-debug/BALCO-T4-Alloy-Project/assets/120302433/a987d98b-dfce-4c75-ba5a-0998a2e9835c)
Multioutput Regression Model:

The project utilizes the MultiOutputRegressor from sklearn.multioutput, which combines multiple single-output regressors into a multioutput regression model.
The base estimator used in this project is GradientBoostingRegressor from sklearn.ensemble.

Model Training and Evaluation:

The multioutput regression model is trained on the training data (X_train, Y_train).
The model's performance is evaluated by calculating the mean squared error (MSE) and R2 score on both the training and test sets.
The MSE and R2 score are calculated for each target variable separately.

Graph Plotting:
The code includes a section to plot graphs that depict the relationship between input features and target variables, along with the actual and predicted values.
Each graph represents one target variable and shows the scatter plot of the actual values (blue) and predicted values (red) against the corresponding input feature.
The graphs provide visual insights into the model's performance and how well it captures the relationships between the features and targets.
![image](https://github.com/rishi-debug/BALCO-T4-Alloy-Project/assets/120302433/b875dad8-2e06-4449-ac01-ce6ac4ffcd23)

