# Positive-Negative-Review-using-NLP

Using Natural Language Processing (NLP) to identify whether the review is positive or negative

## Dataset

The dataset consists of 1000 reviews of certain restaurant given by the customers. In the review column are the reviews given and the liked column states if the review is positive or not (1 for positive and 0 for negative)

## NLP in action

Before applying the machine learning models, the text is cleaned and the bag of words model is implemented. After that the dataset is split into 80/20 (train/test). For this particular case, Naive Bayes is used to train the reviews and prediction is made into the test reviews.

The confusion matrix is given below.

![cm_nlp](https://user-images.githubusercontent.com/14214659/71614540-ef78cb00-2bb4-11ea-8fa2-89ea3d82c58e.png)

## Conclusion

The confusion matrix shows 73% accuracy which is OK for this small dataset. In order to increase the accuracy and other performance matrics, huge dataset can be trained and similarly other ML models can be used to compare the predictions.
