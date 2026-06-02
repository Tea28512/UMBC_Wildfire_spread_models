Each file is a machine learning model. The models with _spatial are models that use spatial context in a 3x3 neighboorhood around each pixel. The models predict the wildfire spread from one day to the next day. The models are from Scikit-learn, and the ensemble model is made out of a logistic regression model and random forest model, with a logistic regression model as the final predictor.

Each of the model files also have code to 

Dataset used: https://www.kaggle.com/datasets/fantineh/next-day-wildfire-spread/data?select=next_day_wildfire_spread_eval_00.tfrecord from the paper Next Day Wildfire Spread: A Machine Learning Data Set to Predict Wildfire Spreading from Remote-Sensing Data (Huot, et al.)

To run a model, paste the file path of your dataset, then run the code. 
