# LAB1_MNIST_MLP_Pytorch_Ignite_Kears
In this notebook, I have built a deep neural network on MNIST handwritten digit images to classify them.


In this notebook, we create a Multilayer Perceptron (MLP) model of the MNIST dataset.

  * Multilayer Perceptrons (MLPs) usually mean fully connected networks, that is, each neuron in one layer is connected to all neurons in the next layer. The "fully-connectedness" of these networks makes them prone to overfitting the data.

  * These MLP models are also referred to as either deep feedforward networks or feedforward neural networks. MLPs are common in simple logistic and linear regression problems.

  * So, the objective is to create a neural network for identifying numbers based on handwritten digits. For example, when the input to the network is an image of a handwritten number 8, the corresponding prediction must also be the digit 8.

  * To both train and validate a neural network, there must be a sufficiently large dataset of handwritten digits.

The Modified National Institute of Standards and Technology dataset or MNIST dataset for short, is often considered as the Hello World! of deep learning and is a suitable dataset for handwritten digit classification.It is used to explain and validate deep learning theories because the 70,000 samples it contains are small, yet sufficiently rich in information (MNIST dataset is described later).

[![Year-In-Review](https://en.wikipedia.org/wiki/MNIST_database#/media/File:MnistExamples.png)


In this tutorial, you will:

    1* Train and evaluate a tf.keras model for MNIST from scratch.
    2* Train and evaluate an ignite model for MNIST from scratch
    3* Train and evaluate a model for MNIST using Pytorch
    4* Logging with Tensorboard
