# Face Mask Detection using Convolutional Neural Networks

This project aims to develop a face mask detection system using Convolutional Neural Networks (CNNs). The model is trained on a dataset containing images of people with and without face masks, obtained from Kaggle.

### Introduction

The COVID-19 pandemic has emphasized the importance of wearing face masks as a preventive measure against the spread of the virus. Automated systems for detecting whether individuals are wearing masks can aid in enforcing safety protocols in public spaces. This project utilizes CNNs to accurately identify whether a person is wearing a face mask or not.

### Output

# With Mask
![Screenshot 2024-03-21 211612](https://github.com/dineshrx/Face-Mask-Detection-using-CNN/assets/144202549/f87b48d0-df2a-47a9-8a5a-cc395c28110e)
# Without Mask
![Screenshot 2024-03-21 211546](https://github.com/dineshrx/Face-Mask-Detection-using-CNN/assets/144202549/2e2c1283-8373-4960-9355-36bebac6d06b)


### Installation

Ensure the Kaggle library is installed to access the dataset

### Dataset
Download the 'Face Mask Dataset' using the Kaggle API and extract the images for training the classifier:

### Preprocessing
Perform image preprocessing tasks such as resizing, labeling, and conversion to numpy arrays in preparation for modeling.

### Model Building
Split the dataset into training and testing sets, construct a CNN, train the model, and evaluate its performance.

### Predictions
Utilize the trained model to make predictions on new images and determine whether they are wearing face masks or not.

