# Deep-learning-based-emotion-analysis

This project uses word vectors based on deep learning to classify the emotion of the politicians' speeches. 

First, transform the raw Strings to documents and assign a unique label to each of them to conduct Doc2Vec learning. This results in one vector per document. To determine the quality of the document vectors the use of a PCA reduces the 200 dimensional vector space to two dimensions and further plots the vector representation of each document in a scatter plot. 

In the view of the JavaScript Scatter Plot it is evident that the document vectors are divided into two clusters for the two sentiments. The next step is to partition the dataset and train a predictive model on the created document vectors to perform classification.


![YuruLi](https://github.com/YuruLiForPhDApplication/deep-learning-based-emotion-analysis/blob/master/deep%20learning%20method.jpg)
