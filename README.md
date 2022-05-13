# Stock-Market-Analysis-and-Modeling
This repository contains code in a jupyter notebook to train a LSTM on the last 20 years of S&P500.
The purpose is to enable the modeling and potential prediction of the stock market to the degree which is possible with machine learning. 
It cannot predict the market perfectly or account for random events. This was mostly me experimenting with LSTMs but it came out cool regardless.

# Requirements
-Anaconda
-Juypter Notebook support
-Python 3
-Tensorflow
-Numpy
-Pandas
-Matplotlib
-Keras
-Sklearn
-Numba
-Cuda* (not required but highly recommended)

# Run Instructions
Assuming you have all the requirements you should just be able to run the jupyter notebook in order
Guide on how to do that can be found here (https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)

# Issues:
-Currently loading and saving the model seems to be bugged on certain systems
-If you are unable to load the model out right simply retrain it and it should provide generally similar results
-I strongly advise having a gpu accelerated system capable of using cuda as it speeds up tensorflow training quite a lot