# Machine-Learning-Project-Using-Python

The goal of the project is to classify a donor-recipient
pair as either a "good" or "not good" match where a "good" match is determined by
the Human Leukocyte Antigen (HLA) pairings. An HLA mismatch count of 0 or 1 (out
of 6 total pairings) is considered "good." The project uses 5-fold cross validation
with logistic regression, random forest, and multilayer perceptron for classifying
each pairing.  After a feature selection process and data cleaning, the created
models all were successful in predicting whether a match was good or not, with
random forest performing the best and logistic regression performing the worst.
Measured metrics include accuracy, balanced accuracy, F1-score, and others.
