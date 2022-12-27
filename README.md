# Leaf-Counting-classification-and-Regression-using-VGG-16
In this assignment Using Pre-trained vgg16 ON leaf counting dataset and improve the results by regularization and data augmentation
 ## DataSet

Dataset containing 9372 RGB images of weeds with the number of leaves counted. The images are collected in fields across Denmark using Nokia and Samsung cell phone cameras; Samsung, Nikon, Canon and Sony consumer cameras; and a Point Grey industrial camera.



## Data Preparation Load data using Image data loading from keras and split training set into training 80% and validation 20 % and load testing dataset 100 files ith image size 128*128
## Models

## Classification ( Base Model)

VGG-16 remove the top layer and adding 3 fully connected layer the last layer contain the number of class =5 img_1.png

## Regression Using VGG-16 but change the last layer to be 1

## Improve the model to deal with dataset 1-Using Data Augmentation (in-place/on-the-fly data augmentation) that transform each image in the batch and that randomly transformed batch will use the randomly transformed data( augmentation) is done at training time 2- adding Batch Normalization and Dropout
