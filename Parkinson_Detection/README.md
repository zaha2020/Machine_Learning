# Detecting Parkinson disease using signals of speech data with ensemble learning

## Decription:

This Project is a group work with [Amirhossein Mesbah](https://github.com/amirhosein-mesbah). in this project we used signals of speech data for a binary classification task to check if the person to whom the sound belongs has Parkinson's disease or not.  

The data used in this project is related to an article with the following title by Jefferson S.Almeida et al:

"Detecting Parkinson’s disease with sustained phonation and speech signals using 
machine learning techniques"

We implemented the methods used in this paper for data preprocessing, dimensionality reduction and model training. Also, in addition to these cases, we also used ensemble models for training and better performance.

## Result:
The best performance was related to the ensemble model using KNN algorithm, whose accuracy was equal to 96,10%. The results of the rest of the models are available in the table below.

| Algorithms      | Accuracy% |
| ----------- | ----------- |
| Logistic regression      | 87,23       |
| SVM   | 93,97        |
| Decision Tree   | 84,04        |
| KNN(K=1)   | 94,33        |
| MLP   | 91,84        |
| RBF   | 93,26        |
| Ensemble   | 96,10        |
