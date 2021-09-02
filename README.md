# Yoga-Recommendation-system
**Objective** <br />
To build a model that uses NLP and Deep Learning techniques to recommend yoga asanas for the benefit of the body.<br />
*****
**Approach** <br />
● Extracted the data from Asana Pranayama Mudra Bandh using PyPDF2, a PDF toolkit library in Python<br />
● Cleaned and parsed the data using RegEx and NLP libraries to store essential information in the MySQL database<br />
● Implemented Tokenization, Stemming, Lemmatization, One Hot Encoding to convert the data into feature vectors<br />
● Implemented NLP algorithms such as a bag of words, TF-IDF, word2vec, and doc2vec on a dataset of 250+ asanas<br />
● Created a website using Django as the backend framework with the help of HTML and CSS for frontend<br />
● Implemented clustering algorithms: k-means, k-medoids on the feature vectors to cluster asanas based on benefits<br />
● Visualized the clustering by reducing the number of dimensions by using Principal Component Analysis<br />
● Visualized performance by projecting encoded sentence vectors onto a 2D subspace using t-SNE algorithm<br />
*****
**Impact** <br />
● Built the recommendation system that gives a different set of Yoga asanas to users with no set repeating twice<br />
● Successfully suggested top 5 asanas based on user’s health conditions, diseases, and difficulty level<br />
