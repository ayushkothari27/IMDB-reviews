# IMDB-reviews

### Data Cleaning
Removing HTML tags <br>
Removing Punctuations <br>
Converting to lower case <br>
Lemmatization <br>
Removing stop words <br>

### TF-IDF approach accuracy 

SVM - 90.44% <br>
Logistic Regression - 88.9% <br>
Naive Bayes - 88.51% <br>
Decision Tree - 69.33% <br>
Random Forest  - 85.35% <br>

### Neural network with Embedding layer 
Accuracy with 10 epochs - 87%-88% <br>
Adding a Convolution layer - 87%-89% (The time required to train decreases significantly in this case)

### Neural network with Pre-Trained 100 dimension GloVe vectors 
Accuracy with 10 epochs - 86%-88% <br>
Adding a Convolution layer - 85%-87% (The time required to train decreases significantly in this case)


### NBSVM 
NBSVM is an approach to text classification proposed by Wang and Manning (https://nlp.stanford.edu/pubs/sidaw12_simple_sentiment.pdf) that takes a linear model such as SVM (or logistic regression) and infuses it with Bayesian probabilities by replacing word count features with Naive Bayes log-count ratios.
Accuracy - 91.5%
