# Crop_Production_Prediction
A Jupyter python notebook with EDA, Visualisations of Crop Production of India and Production Predictor model for a specific crop.

## About the dataset :
The data is structured data from Kaggel.
https://www.kaggle.com/abhinand05/crop-production-in-india
This dataset provides a huge amount of information on crop production in India ranging from several years. Based on the Information the ultimate goal would be to predict crop production using powerful machine learning techniques.

Content
The content is taken from data.world website
https://data.world/thatzprem/agriculture-india


## About the project:

The dataset has been treated using pandas to get it in modelable form. Visualisation of different crop production using seaborn, matplotlib has been done to get insights from the data.
Machine Learning models were created for Production Prediction like LinearRegression(), SGDRegressor(), Ridge(), Lasso(), DecisionTreeRegressor(), RandomForestRegressor(), SVR() from scikit-learn library and were evaluated for their performance the best model was chosen for testing.

RMSE of the best model was 33 times less than the Standard Deviation of the Target variable.
