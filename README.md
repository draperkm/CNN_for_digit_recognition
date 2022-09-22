# Digit recognizer

The model has been trained on MNIST dataset reaching 99.328% accuracy.

## About the data set used
The MNIST database (Modified National Institute of Standards and Technology database) of handwritten digits consists of a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. Additionally, the black and white images from NIST were size-normalized and centered to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.

<img src="https://github.com/draperkm/Digit-Recognizer/blob/main/MNIST.png" width="600" height="325">


## Architecture

<img src="https://github.com/draperkm/Digit-Recognizer/blob/main/Screenshot%202022-07-06%20at%2020.08.48.png" width="400" height="500">

## What happens in CNNs?

The diagram below shows the processes that an image undergoes before it is fed to a neural network

Convolutional Neural networks is a branch in Deep-learning that is found to be very effective in the field of media processing such as image recognition and audio/video recognition. The dimentionality of the image is reduced before it is fed to a full-connected neural networks, in such a way that all the important features in an image is retained. The important processes in a Convolutional Neural Network in image processing are as follows

1. Convolution
2. Padding
3. Pooling
4. Flatten

<img src="https://github.com/draperkm/Digit-Recognizer/blob/main/Screenshot%202022-07-06%20at%2020.52.57.png" width="600" height="250">

## Imported libraries (Keras implementation)

Pandas 

Numpy

Matplotlib

Sklearn

Keras

Tensorflow

