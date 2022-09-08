# News-Category-Prediction
Prediction of news category through deep learning
This is a deep learnin model based on Deep Learning approach to classify news category.
The dataset includes a total of 41 categories like "politics, comedy , world etc"
The Deep Learning model has been made using keras and by using word embedding technique. It is a technique in which we create vectors of the word which is created keeping different features in mind and then the training set is feeded to model. 
The accuracy of the model is less as of now. The main reason can be the classification of 41 different classes that I assume.
The accuracy of the model is roughly 33%. 

# Steps involved :
Dataset reading
Dataset visualization.
Taking 1000 unique samples from each of the 41 classes, in order to fix the class imbalance.
Train - Test split.
Tokeninig the train set and getting the sequences of the test set as well as train set.
Modelling the model.
Compiling the model.
Model fitting
Model evaluation.
Forming confusion matrix. End
