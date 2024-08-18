# Movie Reviews Sentiment Analysis
This project focuses on sentiment analysis of IMDb movie reviews using various deep learning models. The steps involved include data preprocessing, building an embedding matrix using GloVe, and training models using Keras. Below is a detailed breakdown of each step.

## Model Training
Three different models are trained using Keras to perform sentiment analysis:\

### Simple Neural Network
A basic neural network model with an embedding layer followed by dense layers.

### Convolutional Neural Network (CNN)
A CNN model is used to capture local features in the text data, utilizing convolutional layers.

### Long Short-Term Memory (LSTM)
An LSTM model is trained to capture long-term dependencies in the text data, making use of LSTM layers.

## Evaluation
The performance of each model is evaluated using accuracy, precision, recall, and F1-score on the test dataset.

## Predictions
The best performing model is used to perform predictions on new, real IMDb movie reviews.

## Requirements
* Python
* Keras
* Pandas
* Numpy
* Scikit-learn
* TensorFlow
* nltk
