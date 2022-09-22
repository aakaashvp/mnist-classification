# Convolutional Deep Neural Network for Digit Classification

## AIM

To Develop a convolutional deep neural network for digit classification and to verify the response for scanned handwritten images.

## Problem Statement and Dataset

## Neural Network Model

Include the neural network model diagram.

## DESIGN STEPS

### STEP 1:
->import libraries
->train the dataset
### STEP 2:
-> create the model
-> train the model
### STEP 3:
-> upload the hand written image and predict the output

## PROGRAM
model = keras.Sequential()
model.add(layers.Input(shape=(28,28,1)))
model.add(layers.Conv2D(filters=32,kernel_size=(3,3),activation="relu"))
model.add(layers.MaxPool2D(pool_size=(2,2)))
model.add(layers.Flatten())
model.add(layers.Dense(64,activation="relu"))
model.add(layers.Dense(10,activation="softmax"))

https://github.com/aakaashvp/mnist-classification/blob/7d32ba1c21a9a2a1f46cec4da1807d1a768f5400/Copy_of_Ex03_minist_classification.ipynb

## OUTPUT

### Training Loss, Validation Loss Vs Iteration Plot

 ![Screenshot from 2022-09-22 18-54-09](https://user-images.githubusercontent.com/75235212/191758716-324b0d2d-22e5-4d53-9dcb-7952f8cd0342.png)

![Screenshot from 2022-09-22 18-54-17](https://user-images.githubusercontent.com/75235212/191758729-691a55f2-7e19-474f-bae0-df36841f3607.png)

### Classification Report

![Screenshot from 2022-09-22 18-53-43](https://user-images.githubusercontent.com/75235212/191758682-b032628a-7bc0-4f8a-8b59-9ba813f8c96c.png)


### Confusion Matrix

![Screenshot from 2022-09-22 18-53-54](https://user-images.githubusercontent.com/75235212/191758650-62066cc2-b8df-48e5-9ba4-7135d4a85804.png)


### New Sample Data Prediction
![Screenshot from 2022-09-22 18-54-39](https://user-images.githubusercontent.com/75235212/191758526-e08e3d36-3e46-48fa-922a-389506e0fe4e.png)


## RESULT
The Experiment has been successfully completed
