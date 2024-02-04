# Image Segmentation - Oxford-IIIT Pet

## Problem description

The aim of the following project was to implement multiple models for the task of Semantic Image Segmentation. 

The goal of the Semantic Image Segmentation problem is dividing a given input image into separate parts and assigning each of them a semantic label. Unlike Instance Segmentation, where the aim is to identify and differentiate individual instances of objects, semantic segmentation focuses on labeling each pixel in an image with a class label, such as dog, street, sky etc. This described problem is utilized in plenty of practical scenarios, like for self-driving vehicles, medical image diagnosis, geo-sensing, precision agriculture and more.

## Implemented solutions

The project’s solution to the mentioned problem was creating specialized neural network models, training them on obtained data, then validating and improving the models by modifying the architecture and parameters. The main chosen model architecture was that of a so-called **U-Net**. To improve results, an automatic hyperparameter space search algorithm was put in use. To compare the results with another approach, more models were created utilizing the Transfer Learning tactic. All of the mentioned models were created using Tensorflow Keras library for Python. Furthermore, a completely different approach using a classic algorithm was performed and contrasted against the machine learning procedures.

## Technologies

* Python 3
* Tensorflow
* OpenCV

## Results

<img width="734" alt="segmentation results" src="https://github.com/mhawryluk/pets-image-segmentation/assets/70582973/4106c9a7-316e-4a23-9d45-925c65c607df">
