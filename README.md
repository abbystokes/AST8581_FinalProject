# AST8581_FinalProject
Final Project for AST8581 course Big Data in Astrophysics at the University of Minnesota

Project Plan:

Goal: Classify Type SNIa, SNIb, and other supernova using Machine Learning methods
Motivation: SNIb have an identifying emission line of non-ionized Helium (He1) at 587.6 nm, and the SN1a model successfully classifies SN1a supernovae with an identifying emission line of ionized Silicon (Si II)of 615 nm .

TNS https://www.wis-tns.org/ for more data for SNIb

Project Timeline:
Week 1:
Find dataset with spectrum for each supernova (Lexi)
Import and clean data (All)
Use oversampling method to increase prevalence of SNIb in dataset for training (only ~600 SNIb out of 14,000) (Abby)
Week 2:
Split into test, validation, and training datasets (Jacynda)
Using SVM, MLP, and RF, build classifier to identify SNIb from other supernova types
Logistic Regression (Jacynda)
Build Classifier
Use cross validation to tune model hyperparameters (# estimators, max tree length, etc.) 
Evaluate model performance using accuracy, precision, recall, F1 score, confusion matrix, and ROC curves/AUC (one v. one or one v. all).
Support Vector Machine (Abby)
Build Classifier
Use cross validation to tune model hyperparameters (# estimators, max tree length, etc.) 
Evaluate model performance using accuracy, precision, recall, F1 score, confusion matrix, and ROC curves/AUC (one v. one or one v. all).
Random Forest (Lexi)
Build Classifier
Use cross validation to tune model hyperparameters (# estimators, max tree length, etc.) 
Evaluate model performance using accuracy, precision, recall, F1 score, confusion matrix, and ROC curves/AUC (one v. one or one v. all).
Week 3:
Compare model performance to true model SNIascore (link)
Work on presentation and writeup
