# Facial-Expression-Recognition
Using Convolutional Neural Networks for Facial Expression Recognition.

## Getting dataset and running code
You can download the datasets from Kaggle: https://www.kaggle.com/hyena222/new-test-data and https://www.kaggle.com/hyena222/new-train-data and https://www.kaggle.com/msambare/fer2013. 
You can get the csv version of the Kaggle dataset from 
https://www.kaggle.com/deadskull7/fer2013
The one called "fer2013" is the data set from FER2013 on Kaggle. Another two called new-test-data and new-train-data contain the data set generated using face detection on FER2013.

orb-cnn/face-detection.ipynb contains code for ORB-CNN model and face detection.
cnn-svm-rf-xgboost.ipynb contains code for the CNN-SVM model, CNN-RF model and CNN-XGBoost classifier.
To train the models, the .ipynb can be run directly after downloading the datasets.
