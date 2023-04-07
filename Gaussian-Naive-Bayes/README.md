# Gaussian Naive Bayes Classifier from Scratch

## Introduction
The code provided in this repository is purely for learning purposes only. If you wish to know the derivation of Bayes Theorem, Naive Bayes & Gaussian Naive Bayes, visit https://www.kaggle.com/code/ugenteraan/gaussian-naive-bayes-classifier.

## Dataset

This experiment was done on the Loan Dataset from LendingClub.com.
https://www.kaggle.com/datasets/itssuru/loan-data. The main task here is to classify and predict whether the borrowers paid back their loan in full.

## Result & Discussion

The Gaussian Naive Bayes Classifier achieved an accuracy of 71.8% in the test data. 30% of the data was randomly sampled to be the test data. However, Scikit-Learn's implementation of Gaussian NB achieved a higher accuracy of about 81.8%. Upon checking, it seems like Scikit-Learn's implementation had additional tweakings that allows it to achieve a higher accuracy. 

## References

1) https://www.researchgate.net/profile/Daniel-Berrar/publication/324933572_Bayes'_Theorem_and_Naive_Bayes_Classifier/links/5d837aba92851ceb79143b04/Bayes-Theorem-and-Naive-Bayes-Classifier.pdf

