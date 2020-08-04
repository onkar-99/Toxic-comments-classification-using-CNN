# Toxic-comments-classification-using-CNN

Here two datasets are used one for training and other for testing. 
Based on the trained data, model predicts the comments as Toxic or Not Toxic (binary classification) using CNN and Keras.

Model gave very good accuracy of about 99.04% on training data and 95% on testing data.

EarlyStopping callback has been used to stop training if val_acc reaches 95%. Desired accuracy is received in 5 epochs.
However, if you need higher accuracy, you can comment out the early stopping line and remove callback in fit method and train model.
