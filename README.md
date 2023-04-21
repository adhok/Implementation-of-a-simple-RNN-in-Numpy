# Implementation-of-a-simple-RNN-in-Numpy
A crude implementation of a simple single layered RNN (with backpropagation) using Numpy to classify sentiment.


🧠 Recurrent Neural Networks (RNNs) are a type of neural network designed to process sequential data by using feedback loops to incorporate information from previous time steps. They are important because they can model and generate sequences of arbitrary length, making them useful for tasks such as natural language processing, speech recognition, sentiment analysis, and time series prediction.


👨‍💻 In the Python notebook, a stepwise approach to implementing a single-layered RNN is presented. Using this RNN, we implement sentiment prediction on Olist product reviews (written in Portuguese) using only NumPy, a powerful Python-based computational library for performing linear algebra-based operations. 


🔥 Despite its limitations, the single-layered RNN was able to achieve a fair performance(65%), thus providing compelling evidence of its ability to process sequences.

# Acknowledgement

This repository helped me a lot in understanding the inner workings of RNNs and LSTMs -> https://github.com/CaptainE/RNN-LSTM-in-numpy

# About the RNN

* It has 8 hidden units
* It has 2 output units to predict sentiment ( positive/ negative).
* An accuracy of 65% was achieved.
