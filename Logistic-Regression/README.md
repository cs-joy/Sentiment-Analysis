# Sentiment Analysis Logistic Regression Model
The dataset was loaded and cleaned during the Data Preparation phase by removing HTML tags, punctuation, numbers, converting text to lowercase, and eliminating stopwords. For Feature Extraction, the text was converted into numerical features using `TF-IDF` (Term Frequency-Inverse Document Frequency) with a maximum of `5000` features. `Logistic Regression` was selected for Model Training due to its effectiveness in text classification tasks. The model's performance was assessed during Evaluation using standard metrics such as `accuracy`, `precision`, `recall`, `F1-score`, and a confusion matrix visualization. Finally, in the Deployment stage, the **trained model** and **vectorizer** were saved as `pickle` files for future use, along with a provided `demo script`. Afterwards, evaluated our trained model performance through fully new `test_data.csv`.

## Data Preparation:

i) Loaded the CSV dataset containing [ImDb movie reviews](https://www.kaggle.com/datasets/mantri7/imdb-movie-reviews-dataset) and their sentiment labels (`0=negative`, `1=positive`)
ii) Cleaned the text by removing `HTML tags, punctuation, numbers, converting to lowercase, and removing stopwords`
iii) Split the data into `80%` training and `20%` testing sets

## Model Training:

i) Used `TF-IDF` vectorization to convert text to numerical features
ii) Trained a `Logistic Regression` classifier as the primary model

## Evaluation:

i) Calculated standard metrics: `accuracy`, `precision`, `recall`, and `F1-score`
ii) Generated a `confusion matrix` visualization
iii) Saved both the trained model and vectorizer for future use

## Demo Script:

i) Created a function called `predict_sentiment()` that takes user input text and predicts its sentiment using the trained model

## Tools Used:

i) Jupyter Notebook and Python as IDE
ii) Pandas for data manipulation
iii) NLTK for text processing
iv) Scikit-learn for model training and evaluation
v) Matplotlib/Seaborn for visualization

## Results:
The model achieved the following performance metrics on the test set(20%)`[part of train_data.csv]`:

| Accuracy | Precision | Recall | F1-score |
| -------- | --------- | -------| ---------|
|  0.8810  |   0.8664  | 0.8982 |  0.8820  |


and performance metrics on the original `test_data.csv`(90%):
| Accuracy | Precision | Recall | F1-score |
| -------- | --------- | -------| ---------|
|  0.8771  |   0.8731  | 0.8822 |  0.8776  |
