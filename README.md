# Transforming-handwritten-text

The goal of this project is to make the machine understand the handwritten samples of digits and alphabets and predict the class of those objects accurately.  

Dataset used is eminst balanced which has 112000 records for training and 18000 records to test. All these handwritten samples are taken as images and they are classified in one of the 47 classes. These samples can be explained as numerical of 0-9 and alphabets from a-to z including upper case and lower case. Dataset is balanced with about 2400 observations in each class for train dataset and 400 observations for each class in test dataset.  

The input images are represented as 28*28*1 (meaning only one channel which means the images are of grey scale). 28*28 gives 784 input features each feature representing the pixel value in the image which ranges from 0-255.  
Link to data- https://www.kaggle.com/crawford/emnist?select=emnist-letters-test.csv
