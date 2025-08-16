# Sentiment Analysis using LSTM

## Sentiment Analysis is a classification of emotions (in this case, `1` as positive and `0` as negative) on text data using text analysis techniques (I use LSTM).

The purpose of sentiment analysis is to assess written text and classify its emotional tone as positive, negative, or neutral. Here i only worked tone as positive or negative and use LSTM and Keras.

LSTM, short for Long Short-Term Memory, is an RNN-based architecture employed in deep learning models

As an open-source Python library, Keras supports deep learning and integrates with TensorFlow as its backend.


## Dataset

The dataset used in this analysis is the [IMDB Movie Reviews](https://www.kaggle.com/datasets/mantri7/imdb-movie-reviews-dataset) from Kaggle, featuring two columns—review texts and binary sentiment labels (1 for positive, 0 for negative).


## Architecture

1. Embedding Layer

2. Bidrectional LSTM Layer

3. Dense (activation function using ReLu and Sigmoid)

4. Optimizer: Adam, Loss Function: Binary Crossentropy


## References

1. [Tensorflow](https://www.tensorflow.org/)

2. [Keras](https://www.tensorflow.org/api_docs/python/tf/keras)

3. [IMDB Moview Reviews Dataset](https://www.kaggle.com/datasets/mantri7/imdb-movie-reviews-dataset)
