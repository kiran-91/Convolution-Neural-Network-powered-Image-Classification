# Convolution-Neural-Network-powered-Image-Classification
## This is an academic project assosiated with Vellore Institute of Technology (June 2023-December 2023)

## Project Overview 
This project develops a Convolutional Neural Network (CNN) to classify images as expressing either happiness or sadness. The goal is to create a user-friendly tool that can analyze uploaded images and provide real-time emotional predictions

## Methodology 

1. **Data Preparation**: Collect and preprocess image data, ensuring consistent size, format, and normalization.
2. **Model Design**: Determine the CNN architecture, including the number and type of convolutional/pooling layers, filter sizes, strides, and activation functions.
3. **Training**: Split data into training, validation, and test sets. Train the CNN by updating weights based on loss.
4. **Evaluation**: Test the trained CNN on unseen data to assess performance metrics like accuracy, precision, recall, and F1 score.

## Model Used 
1. Input Shape
The input shape of the network is (256, 256, 3), which means that the input image is of size 256x256 pixels and has 3 channels (RGB).
Parameters
2. The first convolutional layer has 16 filters, the second convolutional layer has 32 filters, and the third convolutional layer has 16 filters. The number of filters determine the number of feature maps produced by each layer. The dense layers have 256 and 1 units respectively.

## Architecture 
![image](https://github.com/user-attachments/assets/9f0c8697-211a-4f7e-83ef-d43e2a7153a2)

## Result
The model achieves over 96% accuracy in classifying human faces as expressing happiness or sadness. Users can upload their own images and get instant emotional predictions.
