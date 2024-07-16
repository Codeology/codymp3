# cody.mp3 🎧🎵 - Codeology Sp23

## 🥑 Overview
In this project, you’ll be learning key fundamentals of data science and machine learning, focusing on audio processing. First, we’ll be running you through the basics of modeling and neural networks with our own audio sets, and through the help of libraries like Tensorflow, Librosa, and Sklearn, we’ll be writing code capable of processing and classifying mp3 files. Later on, you’ll be able to apply these concepts to your own sets of audio files, and come out of the project with a basic ML foundation and the skills to create your own models in the future!

## 👫 Project Members
Project Leaders: Michael Zhang, Mizuho Li\
Project Developers: Alena Chao, Allan Chen, Andrew Zhang, John Glen Siy, Raghav Punnam

## 💻 Data Preprocessing
Learned how to manipulate and query Pandas dataframes as well as utilize various NumPy operations.

## 📈 Exploratory Data Analysis
Used Matplotlib, Seaborn, and Librosa to visualize song samples, specifically their waveforms. Because we were trying to classify their genre, I noted any distinctions between the waveforms between genres.

## 🤖 Classification
1. K-Nearest Neighbors (KNN): "Scores” training data off certain features and encodes them into data points then predicts using “k” nearest data points to the test data using euclidean distance (k is arbitrary). Implemented with Sklearn.

2. Support Vector Machine (SVM): Encodes data and tries to find optimal “hyperplane” between categories, Effective for higher dimensional data, but risk overfitting. Also Implemented with Sklearn.

3. Convolutional Neural Network (CNN): Machine learning model that uses various parameters and backpropogation to "learn" a good latent space based off the task. Implemented with tensorflow and Keras.
