# Deep-Learning-Approaches-to-Financial-Markets -

This research project implemented several Deep Learning approaches to identify and predict the trajectory of stocks in the pharmaceutical industry during the   Covid-19 pandemic. The paper was titled: 

------------------------------

'Deep Learning for Financial Markets - Exploring Hyperparameter Tuning for Optimised Computational loads'
A link to the paper is: https://tinyurl.com/bd9pm8jr

------------------------------

The code in the .ipynb notebook uses several different tools/mechanisms: 

1) Iniially, the Alpha Vantage is API is used to derive information about the stock prices and ratios. 

2) Then, several pre-processing functions are implemented. This included - filling in null values, creating a benchmark price to test upon, reformatting the shape for the neural network. 

3) A LSTM network is then defined using Tensorflow and training data is implemented. 

4) Further, the model results is compared to other models (both specific to the stock market and in general). These include - Facebook Prophet, Azure ML, Google Cloud AutoML, and IBM Watson ML. 
