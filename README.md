# ML_Project_DigitRecognition_USPS

# Extraction Methods of Handwritten Digit Recognition Tested on the USPS Database

Handwritten digit recognition has recently been of
very interest among the researchers because of the evolution of
various Machine Learning, Deep Learning and Computer Vision
algorithms , this paper deals with an handwritten digit recognition
system and a method of extraction of characteristics based on the
digit form, this method is tested on the USPS handwritten isolated
digit database (20000 images in learning and 1500 images in test).
In this report, I compare the results of some of the most widely
used Machine Learning Algorithms like SVM, KNN, PCA, LDA,
QDA, LRC, MLP, ABC, DTC, HOG + SVM, Bayesian, SGD &
RFC this work has achieved approximately 80% of success rate
for USPS database identification.

Our model works in three steps: 1) Preprocessing, 2) Features
extraction and 3)Use classification Method. In the
preprocessing, we have some basic image processing to
separate numbers from real samples or preparing data from
dataset (which is reshaped from images to the vectors) and then
in the second part, we extract features which is very distinguishable descriptor for digits recognition where we
divide an input image into fixed 28\*28 cells and we represent
each digit with a vector of features. The summary of several
classification methods that used in this paper are: QDA that is
a classifier with a quadratic decision boundary, generated by
fitting class conditional densities to the data and using Bayes’
rule, RFC is a random forest is a meta estimator that fits a
number of decision tree classifiers on various sub-samples of
the dataset and uses averaging to improve the predictive
accuracy and control over-fitting, DTC is a Decision Tree
Classifier, repetitively divides the working area(plot) into sub
part by identifying lines. repetitively because there may be two
distant regions of same class divided by other, MLP is a Multilayer Perceptron classifier, this model optimizes the log-loss
function using LBFGS or stochastic gradient descent and SVM
a Support Vector Machine (SVM) is a discriminative classifier
formally defined by a separating hyperplane. In other words,
given labeled training data (supervised learning), the algorithm
outputs an optimal hyperplane which categorizes new
examples.

# Dataset

You can download USPS dataset from here:

https://www.kaggle.com/datasets/bistaumanga/usps-dataset

put dataset into your path directory and then run and enjoy!
