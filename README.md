# K-NEAREST NEIGHBOURS

This project implements from scratch a K Nearest Neighbours Classifier to two datasets to predict the correspondent label given new observations. The main goal is to find the right K number that gives the best accuracy for both examples.

The first example is the Iris dataset which can be found in the scikit-learn package. It contains 150 observations of iris flowers and 4 features that measure the size of its sepals and petals. The final target is a categorical variable of the three possible species of iris (iris setosa, iris virginica and iris versicolor). 

The second one is the ionosphere dataset, it has been downloaded from a text file and it gives information of a radar system in Goose Bay, Labrador, using 351 samples and 34 features. If the sample shows some structure in the ionosphere, the final label will be "Good(+1)", otherwise it returns "Bad(-1)".

Both datasets are already normalised, so they do not need any pre-processing before implementing the model. However, as it is a supervised learning approach, the data has to be previously split into training and test sets. The objective is to find the best test accuracy score for every example. 
