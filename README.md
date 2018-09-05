# Kickstarter-Success-Prediction
 
Dataset: 
https://www.kaggle.com/oscarvilla/kickstarter-nlp 
 
Objective: 
Predict success rate of Kickstarter projects given the blurb/short description of each project 
 
Methods Used: 
Bag of Words representation with Linear SVM 
Bag of Words representation with RBF SVM 
LSTM with learnable words embedding (randomly initialized) 
GRU with learnable words embedding (randomly initialized) 
 
Results: 
Linear SVM: Training - 37.11%, Test - 34.80% 
RPF SVM: Training - 36.56%, Test - 37.06% 
LSTM: Training - 55.07%, Test - 54.66% (after 100 epochs) 
GRU: Training - 57.71%, Test - 57.04% (after 100 epochs) 
