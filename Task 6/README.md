Task Objective
Develop a machine learning model to predict house prices based on housing and demographic features. The objective is to compare a traditional regression algorithm with an advanced ensemble learning method and determine which model provides more accurate house price predictions.
Dataset Used
Dataset: California Housing Dataset
Source: Scikit-learn Built-in Dataset
Records: 20,640 housing instances
Features:
Median Income (MedInc)
House Age (HouseAge)
Average Rooms (AveRooms)
Average Bedrooms (AveBedrms)
Population
Average Occupancy (AveOccup)
Latitude
Longitude
Target Variable:
Median House Value (Price) measured in units of $100,000
Models Applied
1. Linear Regression
A fundamental regression algorithm that models a linear relationship between input features and house prices.
Fast, simple, and easy to interpret.
Trained on standardized feature values.
2. Gradient Boosting Regressor
An ensemble learning algorithm that combines multiple decision trees.
Uses boosting techniques to improve prediction accuracy.
Configured with:
100 estimators (trees)
Maximum depth of 4
Learning rate of 0.1
Designed to capture complex non-linear relationships in the data.
Key Results and Findings
The California Housing dataset was successfully loaded and analyzed.
No missing values were found in the dataset.
Exploratory Data Analysis (EDA) revealed:
Distribution of house prices across California.
Strong positive relationship between median income and house prices.
House age showed a moderate influence on property values.
Several features demonstrated varying degrees of correlation with house prices.
Data was split into:
80% Training Set
20% Testing Set
Feature scaling was applied using StandardScaler to improve model performance.
Model performance was evaluated using:
Mean Absolute Error (MAE) – Average prediction error.
Root Mean Squared Error (RMSE) – Penalizes larger prediction errors.
Visualization techniques included:
Price distribution histograms.
Correlation analysis.
Actual vs Predicted comparison plots.
Scatter plots with perfect prediction reference lines.
The model with the lower MAE was selected as the best-performing model.
In most cases, Gradient Boosting Regressor outperforms Linear Regression because it can learn complex patterns and non-linear relationships within housing data.
Scatter plots showed that better-performing models produce predictions closer to the ideal diagonal line, indicating higher accuracy.
