# YOUTUBE_SPAM_COMMENT_DETECTION
# YouTube Spam Detection:
This repository contains code for a YouTube spam detection model based on a recurrent neural network (RNN) with Long Short-Term Memory (LSTM) cells. The model is built using TensorFlow and Keras. Also we have used a pywidgets for checkig our comment that is wheather it is spam or ham.

# Dataset:
The code is designed to work with the YouTube Spam Collection dataset, which includes comments from different YouTube videos categorized as spam or non-spam. The dataset contains 5 csv files that contains the comments done by the users on the videos from 5 different channels.

# Dataset Source:

(https://www.kaggle.com/datasets/lakshmi25npathi/images)
The dataset we are working on is taken from kaggle.


# Requirements:
Make sure you have the necessary dependencies installed. You can install them using the following command:
Your system must have this libraries installed

ipywidgets
pandas
scikit-learn
tensorflow

# Model Architecture:
The spam detection model is based on a recurrent neural network (RNN) with Long Short-Term Memory (LSTM) cells. The architecture is implemented using TensorFlow and Keras.

A. Layers Overview:
In this layers we have build following layers:
1. Embedding Layer
2. LSTM Layer
3. Dense Layers

B. After building this layers we have we have compiled our model.
C. Trained our model and then Evaluated our model
After evaluating our model accuracy comes out to be 90% to 95%.

# Results
After training the model, the accuracy and classification report are printed, providing insights into the model's performance on the test set.

# Real-Time Spam Detection
A user interface is provided to input comments for real-time spam detection. The prediction is displayed immediately.
