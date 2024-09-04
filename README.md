### Handwritten Digit Classification using Neural Networks
A simple artificial neural network model built with TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

#### Overview
This project uses a neural network to classify digits (0-9) from the MNIST dataset, consisting of 60,000 training images and 10,000 test images.
At the moment, the project contains multiple implementation of the solution. One with no hidden layer that gives about 92% accuracy,and one with 1 hidden layer that gives about 97% accuracy.

#### Model Architecture
1st model:
Input Layer: 28x28 (flattened)
Hidden Layers: None
Output Layer: One dense layer with 10 outputs, Sigmoid activation activation

2nd model:
Input Layer: 28x28 (flattened)
Hidden Layers: One dense layer with 100 neurons, ReLU activation
Output Layer: One dense layer with 10 outputs, Sigmoid activation activation
