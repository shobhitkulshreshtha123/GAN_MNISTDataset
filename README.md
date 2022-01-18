# GAN_MNISTDataset
The project uses Tensorflow and Keras libraries of Python. Since this is author's first attempt at developing GAN's, a lot of help and support was taken from Tensorflow's official website which features a sample GAN. Hence, a large portion of code snippet may resemble the code on Tensorflow's ofical website.

Python and its libraries:
-- Tensorflow and Keras
-- glob
-- matplotlib
-- numpy
-- os
-- PIL


This project is a basic version GAN which has 2 components:

-- A Generator: This is a deep learning neural network that takes input from training dataset and "learns" to "draw" images.

-- A Discriminator: Competing deep learning Neural network that takes input image from generator and labels it as a fake or real based on quality and training dataset. Its a Convolutional Neural Network (CNN) image classifier.

-- Both the Neural Networks, start to gradually "learn" at being better and better at their work during training.

-- Both neural networks consist of 2 layers of aritifical neurons.

-- At the beginning of training, the generator produces vague random lines which get better and better with time and by the end of training, start to resemble the handwritten numbers.

Google Colab for access to GPU and dataset was MNIST

Thg project also creates an animated file at the end that shows the timelapse evolution of handwritten digits as learnt and recreated by the GAN.
