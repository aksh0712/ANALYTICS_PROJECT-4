DATA-SCIENCE_PROJECT--4

Customer Review Analysis for Leading Women Clothing E-Commerce Company.

Business Description: One of the leading women clothing e-commerce company would like to analyze the customer’s behavior by analyzing customer’s demographics and reviews submitted on the Website.

Solution Data Pipelines
1)  Import essential packages for data preprocessing, text classification and Natural Language Processing then read respective data file.

2)  Apply Exploratory Data Analysis on review text feature to determine various metrics such as unique word count, word density, stopword count, average word length, number of words which start with "NO", number of words which ends with "et". so on...
  
3)  Check sentiment polarity for positive and negative reviews. For this package Textblob is used along with its various modules.

4)  Now categorise the sentiments in positive and negative based on sentiment score.

5)  Perform the sentiment analysis by channel, category, sub-category and location.

6)  Split the dataset under train and test. And create user defined functions to clean and preprocess the data.

7)  Perform vectorization on train data. Word Embeddings or Word vectorization is a methodology in NLP to map words or phrases from vocabulary to a corresponding vector of real numbers which used to find word predictions, word similarities/semantics. The process of converting words into numbers are called Vectorization. 

8)  Generate word cloud using word frequency, based on words, for positive reviews, for negative reviews.

9)  Perform vectorization on train and test dataset. And implement topic modeling using gensim. gensim is a module from corpora (we need to import it before use).

10)  Create user defined function for train data to classification the models. And fit the training dataset on the classifier as well as predict the labels on validation dataset.

11)  Build the different models such as Naive Bayes, Logistic Regression & Linear SVC with different vectors (Count Vector & TF-IDF) to get higher accuracy.

12)  Again for Dimensionality Reduction we need to implement Topic Modeling. It is used to classify text in a document to a particular topic. And then, to train LDA (LatentDirichletAllocation) model.

13) To implement Predictive Modelling we apply Machine Learning Techniques such as Logistic Regression and Linear model for better precision and higher accuracy.
