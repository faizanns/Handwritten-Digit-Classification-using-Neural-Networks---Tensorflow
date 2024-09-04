### Handwritten Digit Classification using Neural Networks

A simple artificial neural network model built with TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

#### Overview

This project utilizes neural networks to classify digits (0-9) from the MNIST dataset, which includes 60,000 training images and 10,000 test images. Currently, the project includes multiple implementations:

- **Model 1:** No hidden layer, achieving ~92% accuracy.
- **Model 2:** One hidden layer, achieving ~97% accuracy.

#### Model Architecture

**1st Model:**

- **Input Layer:** 28x28 (flattened)
- **Hidden Layers:** None
- **Output Layer:** Dense layer with 10 outputs, Sigmoid activation

**2nd Model:**

- **Input Layer:** 28x28 (flattened)
- **Hidden Layers:** One dense layer with 100 neurons, ReLU activation
- **Output Layer:** Dense layer with 10 outputs, Sigmoid activation

---

This version improves readability and clarity by organizing the content with bullet points and separating details for each model.
