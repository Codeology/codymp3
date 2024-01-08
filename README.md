# cody.mp3 🎧🎵
Here's the project I did my first semester in [Berkeley Codeology](https://codeology.club/#/). I filled out this notebook, performing data preprocessing, EDA, and song-genre classification with different types of models.

## Data Preprocessing
Learned how to manipulate and query Pandas dataframes as well as utilize various NumPy operations.

## Exploratory Data Analysis
Used Matplotlib, Seaborn, and Librosa to visualize song samples, specifically their waveforms. Because we were trying to classify their genre, I noted any distinctions between the waveforms between genres.

## Classification
1. K-Nearest Neighbors (KNN): "Scores” training data off certain features and encodes them into data points then predicts using “k” nearest data points to the test data using euclidean distance (k is arbitrary). Implemented with Sklearn.

2. Support Vector Machine (SVM): Encodes data and tries to find optimal “hyperplane” between categories, Effective for higher dimensional data, but risk overfitting. Also Implemented with Sklearn.

3. Convolutional Neural Network (CNN): Machine learning model that uses various parameters and backpropogation to "learn" a good latent space based off the task. Implemented with tensorflow and Keras.


