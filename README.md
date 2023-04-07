# SMS-Spam-Detection
The aim of this project is to develop an SMS spam filter to classify the message as spam or ham using NLP based text analytics models.

1) The data considered was text messages belonging to spam and normal category.

2) The data was processed with various text pre-processing techniques like Removing punctuation, white spaces, stop words, Lemmatization, Stemming etc. 

3) The pre-processed data was subjected to vectorization pipeline which tokenizes the words and convert the test messages into sparse data frame. The different vectorization approaches followed were TF, TF-IDF, word2vec, heuristic way.

4) The data frames resulting from the vectorization process were subjected to Dimensionality reduction method like PCA. 

5) The final step involved fitting various Machine Learning classification models and tabulating the results to evaluate the best performing model. 

6) Fitted different machine learning classification models and the best-performing model is Logistic Regression with a 92 percent F1 score.
