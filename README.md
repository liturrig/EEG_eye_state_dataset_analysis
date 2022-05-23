# EEG_eye_state_dataset_analysis
 Individual project for the exam "Mathematics in Machine Learning" of Data Science and Engineering Master's Degree.
 
 The current analysis is about a real dataset, named EEG eye state, related to continuous EEG measurement with Emotiv EEG Neuroheadset.
 The duration of the measurement was 117 seconds. A camera records the eye state and subsequently the state was added manually to a file after analyzing the video frames.
 ’1’ indicates the eye-closed and ‘0’ the eye-open state.
 
 Data exporation:Target distribution,features distribution,Correlations matrix.
 Data Preparation: Normalization,z-score outliers managment, PCA, Oversampling , Undersamplig.
 Methodology: K-fold cross validation, metrics.
 Classification model: SVM, Decision tree, Random Forest, K-nearest Neighbors, Logistic Regressor.
 
 The best model is the K-nearest Neighbors with 0.96 f1 score.
 
