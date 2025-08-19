# cifar10_image_classifier
An image classifier built with PyTorch using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset. This project covers the end-to-end process of a deep learning application, from data pre processing to performance analysis.

# CIFAR-10 Image Classification using PyTorch

## Project Overview

This project involves building a Convolutional Neural Network (CNN) from scratch to classify images from the **CIFAR-10 dataset**. The goal is to correctly identify images across 10 categories: *airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck*.

This served as a hands-on introduction to fundamental Deep Learning and Computer Vision concepts, including tensor operations, convolutional layers, and the model training lifecycle. It was developed to solidify my understanding of PyTorch and neural network mechanics.

## Technical Details

- **Model Architecture:** A custom CNN with two convolutional layers (with max-pooling and ReLU activation) followed by three linear layers.
- **Dataset:** [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) (60,000 32x32 color images).
- **Framework:** PyTorch, with TorchVision for data loading and transformations.
- **Training:** The model was trained for 5 epochs using Stochastic Gradient Descent (SGD) with momentum and Cross-Entropy Loss.

## Key Skills Demonstrated

- **PyTorch Proficiency:** Ability to work with `Datasets`, `DataLoaders`, and the `nn.Module` API.
- **Deep Learning Fundamentals:** Understanding of CNNs, activation functions, loss functions, and optimizers.
- **ML Workflow:** Full pipeline execution including data preprocessing, model training, validation, and performance analysis.
- **Result Interpretation:** Analyzing loss curves and accuracy metrics to gauge model performance.

## Results

The model achieved an accuracy of **XX%** on the test set. (Note: Replace XX with your final accuracy from the output of Cell 7)
