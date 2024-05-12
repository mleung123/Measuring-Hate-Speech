Dataset sourced from http://hatespeech.berkeley.edu. Predictors and other information about the data can be found at https://huggingface.co/datasets/ucberkeley-dlab/measuring-hate-speech/blob/main/README.md

A variety of machine learning models to predict the presence and intensity of hate speech in social media comments. Techniques used include KNeighbors, Decision Trees, XGBoosting, Stacking Ensembles, and RNNs.
Work in progress. The best model currently has a RMSE of 0.506 on train set and 1.764 on the test set. Converting the data to binary values and creating classification models instead yields a 88.41% classification accuracy on training and 88.23% on testing.
