# Sentiment-Analysis
It is an NLP based project work for analyzing the sentiment(positive or negative) of given reviews on the IMDB movie reviews site. Dataset contains 50k reviews and perfectly balanced.

Removed 418 duplicate rows from the dataset.

Extracted two more features(word number and sentence number)

Removed html tags,punctuation marks and stopwords from the data.

Lemmatized the tokens and then vectorized them using word-2-vector technique

Applied various classification models[Logistic Regression,Multinomial Naive Bayes,Random Forest and Support Vector Machine(SVM)]

SVM model gave the best accuracy (87%) and also Precision and Recall was also up to the mark. So SVM model is selected.

Dataset link :- https://www.kaggle.com/datasets/vishakhdapat/imdb-movie-reviews
