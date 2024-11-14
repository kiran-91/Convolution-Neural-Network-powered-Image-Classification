# Convolution-Neural-Network-powered-Image-Classification
## This is an academic project assosiated with Vellore Institute of Technology 

## Project Overview 
In this project, we have developed a Convolutional Neural Network (CNN) based image classification system using OpenCV and TensorFlow. The objective of this system is to distinguish between two emotional states, happiness and sadness, by analysing the content of images. The motivation behind this project is to create a user-friendly tool that allows users to input their own images and obtain predictions regarding the emotional state conveyed in those images. Rather than focusing on standard classification metrics like accuracy or recall, the emphasis here is on providing users with an intuitive, real-time emotional analysis tool.

## Methodology 
Step 1: Data Preparation
•	Collect and preprocess image data, ensuring consistent size, format, and normalization.
Step 2: Model Architecture Design
•	Determine the number and type of convolutional and pooling layers.
•	Choose filter sizes, strides, and activation functions for each layer.
Step 3: Model Training
•	Split data into training, validation, and test sets.
•	Initialize CNN weights randomly.
•	Select an optimizer (e.g., SGD, Adam, etc.) and set learning rate, batch size.
•	Train the CNN by feeding training data and updating weights based on loss.
Step 4: Model Evaluation
•	Test the trained CNN on the unseen test set to assess generalization.
•	Calculate performance metrics (accuracy, precision, recall, F1 score).
Step 5: Deployment and Optimization
•	Integrate the trained CNN into an application or system.
•	Continuously improve the CNN with new data and parameter tuning


## Model Used 
1. Input Shape
The input shape of the network is (256, 256, 3), which means that the input image is of size 256x256 pixels and has 3 channels (RGB).
Parameters
2. The first convolutional layer has 16 filters, the second convolutional layer has 32 filters, and the third convolutional layer has 16 filters. The number of filters determine the number of feature maps produced by each layer. The dense layers have 256 and 1 units respectively.

## Architecture 
![image](https://github.com/user-attachments/assets/9f0c8697-211a-4f7e-83ef-d43e2a7153a2)

## Result
Given images containing human faces, the model will identify the emotion being expressed by the person in each image, specifically whether they are happy or sad with an accuracy of more than 95%

