# Novotel_NLP_Rating_Prediction

This project is part of the project I had to conduct during my Msc at Ecole Polytechnique involving Capgemini consulting.

We were to construct a classifier to predict rating of Novotel Hotels. 
The big challenge in this case lied in the problem of unbalanced labels completely biasing the multinomial classifier we were to construct. 
I tried several methods to adjust this issue (oversampling, undersampling, automatically using SMOTE) whilst paying careful attention to when the <>sampling method was used as to not add bias to the model.

To train the classifier and test it, I constructed a pipeling to apply to a dataframe. 
