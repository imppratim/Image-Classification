# Image Classification Using ResNet 50

We have utilized ResNet-50 for image classification.

Built a Classifier with [MATLAB](https://www.mathworks.com/products/matlab.html).

The network has an image input size of 224-by-224-by-3.

It demonstrates the practical application of the trained ResNet-50 network and showcases how to classify an image using the pre-trained model. Given an input image, this function illustrates the process of feeding it through the network and obtaining predictions for the object or category depicted in the image. This functionality is instrumental in various image-centric applications, including content-based image retrieval, automated tagging, and object identification.

By offering these three distinct functions, our ResNet-50 neural network implementation not only facilitates the creation of custom models but also provides a seamless transition to leveraging the power of pre-trained deep learning models for real-world image analysis tasks. Whether you are a machine learning researcher, computer vision enthusiast, or developer seeking to harness the capabilities of ResNet-50, this project offers a versatile and practical solution to address your needs.
# Usage

This requires [MATLAB](https://www.mathworks.com/products/matlab.html) (R2018b and above) and the [Deep Learning Toolbox](https://www.mathworks.com/products/deep-learning.html).

This NN has three functions:
- resnetLayers: Creates an untrained network with the network architecture of ResNet-50
- assembleResNet: Creates a ResNet-50 network with weights trained on ImageNet data
- Predict: Demonstrates how to classify an image using a trained ResNet-50 network

# Example Predication Output:

![pred_1](https://user-images.githubusercontent.com/52782379/180206911-e1da23f6-f476-4635-8134-7df73871436a.png)

# Deep Network Analyzer: 

![image](https://user-images.githubusercontent.com/52782379/180207037-43892b54-80d1-4b54-afa7-6761009211fd.png)

# Accuracy and Loss Graph

![image](https://user-images.githubusercontent.com/52782379/180206683-c1a03335-76ef-4908-99b6-c8176f70d8ac.png)
