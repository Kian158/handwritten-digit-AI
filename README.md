# handwritten-digit-AI
This project implements a simple feedforward neural network to classify handwritten digits from the MNIST dataset. The network is built using only numpy for computations and does not rely on high-level deep learning frameworks for the model itself.

# Dataset
The MNIST dataset contains 70,000 grayscale images of handwritten digits (0–9) with dimensions of 28x28 pixels. It is divided into:

Training set: 60,000 images

Test set: 10,000 images

The dataset is loaded using keras.datasets.mnist.

# Architecture

Input layer: 784 neurons (28x28 flattened image)

Hidden layer: 64 neurons, sigmoid activation

Output layer: 10 neurons, linear output (softmax is computed during loss calculation)

# Comments
As I learn more about machine learning, I realise it's just a lot of linear algebra. I've studied this a lot with my degree, and the applications here click naturally. Backpropagation is just the chain rule, and while it was confusing at first to find all the different rates of change, it makes a lot of sense now. This project really helped with my understanding, and was a good and classic example to build from scratch. I can see how this can be scaled up, and applied to many things.
