 # Text-Classification

ABOUT : This dataset for this project contains two subparts: one part consisting of mini newsgroups and other of 20 newsgroups. The output of the dataset is a set of 20 different types of newsgroup. The task is to find the category of newsgroup the given file belongs.
The given problem is solved using two methods: self implementation of Naive Bayes as well as inbuilt Multinomial Naive Bayes found in sklearn module.

LINK FOR DATASET USED: http://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups


OVERVIEW OF STEPS DONE:
1. The files are first opened and are cleared of stop words,digits,punctuation marks adn the headers.
2. A dictionary is created having keys as the words predsnt in the files and their frequencies as their corresponding values.
3. The dictionary is then sorted in descending fashion and top k words(k can be any number,4000 here) are chosen as our feature values for training and testing dataframes created.
4. Next, the two main functions of an algorithm i.e. fit and predict are made to implement Naive Bayes.
5. The score finally calculates the accuracy which is 75-80% in case of 20 newsgroups while 65-70% in case of mini newsgroups.
