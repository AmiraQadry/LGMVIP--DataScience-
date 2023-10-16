# Handwritten Digit Classification for MNIST using CNN

This project aims to classify handwritten digits from the MNIST dataset using Convolutional Neural Networks (CNN). The MNIST dataset is a widely used benchmark dataset in the field of machine learning.

## Dataset

The MNIST dataset consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9) in grayscale. Each image is a 28x28 pixel square, resulting in a total of 784 features. 
The dataset is already preprocessed and does not require any further cleaning or preprocessing steps.

The dataset can be accessed and loaded using the `mnist` module from the `tensorflow.keras.datasets` library in Python.

## Dependencies

This project requires the following dependencies:

- Python
- TensorFlow
- Keras
- numpy
- matplotlib

## Results

The test loss and accuracy achieved by the CNN model is 99%. The accuracy represents the proportion of correctly classified digits out of the total number of digits in the test set.

## References

- The MNIST dataset: [MNIST](http://yann.lecun.com/exdb/mnist/)
- TensorFlow library: [tensorflow.org](https://www.tensorflow.org/)
- Keras library: [keras.io](https://keras.io/)
