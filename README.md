# DSCaliforniaHousePricePrediction
The purpose of the project is to predict median house values in Californian districts, given many features from these districts.
Author : Nitesh Pandey

"housing.csv" is the dataset i have used for prediction 
Source : https://www.kaggle.com/subashdump/california-housing-price-prediction

Here, i have uploaded the python file "California Housing Prices.ipynb" which includes the code of the prediction inclusive of 
multiple ML algos also i have used here SciKit, matplotlib, scipy and other libraries.

"my_model.pkl" is the final output

pkl file is, in fact, a serialized pickle file, which means it has been dumped using Python's pickle module.

To un-pickle the data you can:
Python code starts ::

import pickle


with open('serialized.pkl', 'rb') as f:
    data = pickle.load(f)

:: Python code ends here
