# Image-generation

This project implements a Generative Adversarial Network (GAN) using PyTorch to generate synthetic images from the MNIST dataset. The GAN consists of a generator network that learns to generate realistic handwritten digit images, and a discriminator network that tries to distinguish between real and generated images.

## Overview

- The generator and discriminator models use multilayer perceptron (MLP) architectures with LeakyReLU activations and dropout regularization.
- The Binary Cross-Entropy with Logits Loss (BCEWithLogitsLoss) is used for both the discriminator and generator losses.
- The MNIST dataset is preprocessed by scaling the pixel values to the range [-1, 1].
- The training loop alternates between training the discriminator on real and fake images, and training the generator to produce realistic fake images that can fool the discriminator.

## Usage

1. Clone the repository and navigate to the project directory.
2. Make sure you have the required dependencies installed (`torch`, `torchvision`, `numpy`, `matplotlib`).
3. Run the `imagegeneration.ipynb` script to train the GAN model on the MNIST dataset.


