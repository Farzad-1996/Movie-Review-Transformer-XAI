# Movie-Review-Transformer-XAI
In this project, we utilized some models to classify the sentiment
of movie reviews from text data and observed how the models
behaved using Explainable Artificial Intelligence (XAI). At first
dataset was collected and pre-processed. Then the processed
dataset was separated into different train and test sets. The
train set was used to classify using different different machine
learning and neural network based models. The test set was
used after training to evaluate the trained classifiers. Finally,
the performance of the classifiers were compared and evaluated.
After different variations of pre-processing and training steps, the
best accuracy score of 91% was obtained using Roberta LSTM
model. In the trained models, we sent texts that are correctly
classified by RoBERTa models but misclassified by other models.
Finally we figured out the reasons of misclassification with the
help of LIME Algorithm.

# Dataset Details
The dataset used in our model is Sentiment Analysis on
Movie Reviews which was taken from kaggle website :
www.kaggle.com/c/sentiment-analysis-on-movie-reviews/data.
