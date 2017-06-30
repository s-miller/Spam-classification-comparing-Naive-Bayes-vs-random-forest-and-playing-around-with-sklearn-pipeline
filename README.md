# Spam classifier using Naive Bayes (and playing around with sklearn pipelining)

This notebook looks a the UCI SMS Spam Collection dataset and uses an NLP (bag of words) approach to build a spam detector.  We used the sklearn pipeline feature to fit and transform with the count vectorizerand tf-idf transformer and to fit the classifier.  We initially used a Naive Bayes classifier, and then subsequently replaced it with a random forest (n=50 estimators). 

Neither classifier gave false positives (ham classed as spam). 

The random forest resulted in improved recall for spam classification. 

URL for dataset: https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection.
