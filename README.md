## Predicting movie genre from plot summaries using Machine Learning models ##

Our goal was to build movie genre classification models based on the movie plot summary dataset.We build movie genre classification models based on the movie plot summary dataset.

We have used CMU Movie Summary Corpus data set. This data was collected by David Bamman, Brendan O’Connor, and Noah Smith at the Language Technologies Institute and Machine Learning Department at Carnegie Mellon University. It contains 42,306 movie plot summaries extracted from Wikipedia + aligned metadata extracted from Freebase.

###### Algorithms ######

As there have been projects done on this dataset before, we decided to use those results as our baseline and try to get a better prediction. We decided to focus on both shallow learning models (SVM, Logistic Regression, Random Forest) and deep learning models (DNN, CNN, LSTM).

So, to finalize, our attempt is to develop a movie genre prediction system where the main challenge is to deal with the multiple number of tags possible for any movies. For the data preprocessing, we have applied advanced approaches like stemming, tf-idf vectorizer, multilabel binarizer etc. Both statistical and deep learning-based approaches are adopted for the analysis. The significant thing is that, the available evaluating metrics aren’t that effective in judging the performance for multilabel classification. So, we had to develop task specific metrics. We have plan to explore more sophisticated models to improve the applicability of our model.
