# Kickstarter_Success_Prediction
 
Dataset: <br />
https://www.kaggle.com/oscarvilla/kickstarter-nlp <br />
 <br />
Objective: <br />
Predict success rate of Kickstarter projects given the blurb/short description of each project <br />
 <br />
Methods Used: <br />
Bag of Words representation with Linear SVM <br />
LSTM with learnable words embedding (randomly initialized and GloVe initialized) <br />
GRU with learnable words embedding (randomly initialized and GloVe initialized) <br />
CNN with learnable words embedding (randomly initialized and GloVe initialized) <br />
 <br />
Results: <br />
Linear SVM: Training - 37.11%, Test - 34.80% <br />
LSTM (randomly initialized): Training - 55.07%, Test - 54.66% (after 100 epochs) <br />
GRU (randomly initialized): Training - 57.71%, Test - 57.04% (after 100 epochs) <br />
CNN (randomly initialized): Training - 60.83%, Test - 60.33% (after 10 epochs) <br />
LSTM (GloVe initialized): Training - 64.33%, Test - 64.02% (after 100 epochs) <br />
GRU (GloVe initialized): Training - 64.67%, Test - 64.62% (after 100 epochs) <br />
CNN (GloVe initialized): Training - 62.40%, Test - 62.05% (after 10 epochs) <br />
