# Housing-Price-Prediction-using-Regression-Techniques
Data set used : California Housing Dataset from sklearn 
Handle missing values, suplicate values, outliers and necessary data cleaning using min max scaling
Visualize the data and identify relationships between features and the target variable (housing prices).
Apply feature scaling or normalization techniques
Split the data into training, evaluation, and testing sets (suggested ratio 7:1:2)
Implement and evaluate regression algorithms like Linear Regression
Perform k-fold cross-validation to estimate model performance
Perform hyperparameter tuning using techniques like Grid Search
Based on the evaluation MSE, the Grid Search and Linear Regression models perform similarly, with a little better MSE than the K-fold cross-validation. When deciding on the best model, other metrics and considerations such as interpretability, computational complexity, and resilience must be taken into account.
In this scenario, because the performance indicators are similar, we can select the highest performing model as either Grid Search or Linear Regression. If interpretability and simplicity are important, we can choose the Linear Regression model. If we want to prioritize hyperparameter tuning and potentially greater generalization, we can use the Grid Search approach.
