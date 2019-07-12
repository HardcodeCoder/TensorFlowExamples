# TensorFlow

This is a collection of Tensorflow neural network with some of the basic neural networks

## Getting started

Open the *.ipynb in [Google Colab](https://colab.research.google.com/) and run the code blocks.

### 1. Neural Network to Predict the output of linear algorithms

Convert_celcius_to_farenheit_using_tensorflow.ipynb

It is a simplest neural network that can learn the algorithm given the input and output.
Unlike the classical programs (where input and the algorithm is defined and the program returns the result), 
this neural network tries to learn the algorithm that maps the input to the output.

The neural network is feed with a list of training inputs, for example different values of x in y = 2x + 10) and the
corresponding output. The neural network then tries to map the input x to the output y and in this learning phase
it predicts the relation which in this case is the equation itself.


### 2. Neural Network to classify flower images using Transfer Learning

Classifying_flowers_with_transfer_learning.ipynb

This neural network classifies images of flowers from 
tensorflow dataset [tf_flowers](https://www.tensorflow.org/datasets/datasets#tf_flower) using a pre trained model
of [MobileNet](https://tfhub.dev/google/tf2-preview/mobilenet_v2/feature_vector/2) image classifier.



