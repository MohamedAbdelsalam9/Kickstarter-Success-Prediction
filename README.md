# Kickstarter-Success-Prediction
 
Dataset: <br />
https://www.kaggle.com/oscarvilla/kickstarter-nlp <br />
 <br />
Objective: <br />
Predict success rate of Kickstarter projects given the blurb/short description of each project <br />
 <br />
Methods Used: <br />
Bag of Words representation with Linear SVM <br />
Bag of Words representation with RBF SVM <br />
LSTM with learnable words embedding (randomly initialized) <br />
GRU with learnable words embedding (randomly initialized) <br />
 <br />
Results: <br />
Linear SVM: Training - 37.11%, Test - 34.80% <br />
RPF SVM: Training - 36.56%, Test - 37.06% <br />
LSTM: Training - 55.07%, Test - 54.66% (after 100 epochs) <br />
GRU: Training - 57.71%, Test - 57.04% (after 100 epochs) <br />
