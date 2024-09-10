# Fake_news_classification-
The proliferation of fake news has become a major concern in the digital age. This project aims to address this issue by using machine learning models to classify news titles as either fake or real based on textual data. The project involves the application of various NLP techniques to preprocess the data and several machine learning algorithms to predict the authenticity of news titles.

**DATASET**

The dataset used in this project contains news titles labeled as Fake or Real. The data was preprocessed to remove noise, tokenized, and lemmatized to convert the text into a format suitable for analysis.
The dataset was taken from Kaggle.
https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification 



**Workflow**

Text Preprocessing:

Tokenization: Splitting the text into individual tokens (words).

Lemmatization: Converting words to their base forms.

Data Cleansing: Removing stopwords, special characters, and numbers.




**Vectorization:**

CountVectorizer: Converts text data into a matrix of token counts.

TFIDFVectorizer: Converts text data into a matrix of TF-IDF features.




**Modeling:**

Applied machine learning algorithms such as:

Logistic Regression,
Support Vector Classifier (SVC) and 
Random Forest Classifier
Models were trained using both CountVectorizer and TFIDFVectorizer features.



**Evaluation:**

The models were evaluated using Classification Reports and Confusion Matrices to assess their performance.



