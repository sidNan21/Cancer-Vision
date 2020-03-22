# Identifying Invasive Ductal Carcinoma with Computer Vision

Final Project for CS 4501: Computer Vision at UVA. Tests the effectiveness of ML based approaches for cancer detection.

## Abstract

Disease identification has been a hot topic in computer vision in the past few years as deep learning has become more feasible and gained traction. In our project, we explore the use of ML classifiers and pre-trained deep neural networks, including ResNet variants, in order to identify invasive ductal carcinoma (the most common type of breast cancer) from histopathology images. We utilized a Kaggle dataset created from sampling 277,524 50x50 pixel images from a set of 162 whole mount slide images of Breast Cancer scanned at 40x magnification in order to train (using a 90/10 train/validation split) k-nearest neighbors and softmax classifiers which were used to classify whether images contained instances of invasive ductal carcinoma. In addition, we utilized pre-trained variants of the ResNet neural network for the same classification task and compared the validation loss and accuracy of the models.

## Contributors

+ Siddharth Nanda
+ [Vismita Uppalli](https://github.com/vuppalli)
+ [Dale Wilson](https://github.com/dswilson4)