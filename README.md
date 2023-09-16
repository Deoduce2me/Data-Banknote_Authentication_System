# Data-Banknote_Authentication_System
Data set Banknote Authentication is taken from the UCI repository: https://archive.ics.uci.edu/ml/datasets/banknote+authentication . Data were extracted from 400-by-400-pixel images that were taken from genuine and forged banknote-like specimens. Wavelet Transform was used to extract features from the images. The data set has 4 features and a class label as the last column. The labels are 0 and 1 where 0 corresponds to genuine banknote, and 1 corresponds to forgery.

The data set is comma-delimited and is stored as data_banknote_authentication.txt.

The aim of this assignment is to predict the labels of the first and the last column.

The scope of the work is to import the data, plot the features create a classifier or discriminant function that would be used to predict two of the specified features of interest.

Having predicted, a confusion matrix would be generated from the predicted labels and true labels, Confusion matrices compare True Positives, False Positives, True Negatives, and False Negatives and metrics like recall, f10, accuracy, and precision would be gotten from the confusion matrix to give performance evaluation of the discriminant function.
