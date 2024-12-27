# GEN-AI-image-generator

A Generative Adversarial Network (GAN) designed to generate realistic images from random noise. This project demonstrates how GANs work by training on a dataset of handwritten digits (e.g., MNIST) to create images resembling real data.

**Overview**
GEN-AI Image Generator leverages a GAN architecture to learn and mimic patterns in image data.

The Generator creates fake images from random noise.
The Discriminator distinguishes between real and fake images.
Together, they compete and improve until the Generator produces realistic images.
The project uses the MNIST dataset (28x28 grayscale images of digits) as a training set.

**Features**
Custom implementation of Generator and Discriminator networks.
Visualization of generated images after every training epoch.
Training process with detailed logs for loss metrics (Generator and Discriminator).

**Technologies Used**
Python
PyTorch for neural network implementation.
Torchvision for dataset and image utilities.
Matplotlib for visualizing generated images.

