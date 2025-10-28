# House-Price-Prediction-using-ML
House Price Prediction using Machine learning
The House Price Prediction for Bangalore City project aims to develop a machine learning model that can accurately predict the price of a house based on key features such as location, total square footage, number of bedrooms (BHK), and number of bathrooms.

The project is built using Python, leveraging powerful libraries like pandas, NumPy, scikit-learn, and matplotlib for data analysis, visualization, and modeling. The model is trained on a real estate dataset of Bangalore, containing property listings across multiple localities.

After preprocessing — which includes data cleaning, handling missing values, feature engineering, and one-hot encoding of locations — several regression algorithms such as Linear Regression, Lasso Regression, and Decision Tree Regressor are applied. The best model is selected using GridSearchCV to ensure optimal hyperparameter tuning.

Finally, the trained model is serialized using Pickle, and a Flask web application is built to provide an interactive interface where users can input property details (like location, area, BHK, and bathrooms) and get an instant price prediction.

Technologies and tools Used:
1. Python
2. Numpy and Pandas for data cleaning
3. Matplotlib for data visualization
4. Sklearn for model building
5. Jupyter notebook, visual studio code and pycharm as IDE
6. Python flask for http server
7. HTML/CSS/Javascript for UI

Machine Learning Algorithms Tested:
1. Linear Regression
2. Lasso Regression
3. Decision Tree Regressor
