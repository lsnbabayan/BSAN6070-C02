# BSAN6070-C02
Class Assignment 02
This assignment focuses on using the Naive Bayes maudet to filter and label emails as either Spam or Not Spam.
The libraries needed and/or for this environment are the following:
  import os
  import numpy as np
  from collections import Counter
  from sklearn.naive_bayes import GaussianNB 
  model = GaussianNB()
  from sklearn.metrics import accuracy_score
The data source is provided in the pathway TRAIN_DIR = "Data/train-mails" and TEST_DIR = "Data/test-mails", so it should be accessable to everyone in the class.

