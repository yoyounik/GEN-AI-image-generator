# GEN-AI-image-generator

A Generative Adversarial Network (GAN) designed to generate realistic images from random noise. This project demonstrates how GANs work by training on a dataset of handwritten digits (e.g., MNIST) to create images resembling real data.

**Overview** <br>
GEN-AI Image Generator leverages a GAN architecture to learn and mimic patterns in image data.<br>

1. The Generator creates fake images from random noise.
2. The Discriminator distinguishes between real and fake images.
3. Together, they compete and improve until the Generator produces realistic images.
4. The project uses the MNIST dataset (28x28 grayscale images of digits) as a training set.

![image](https://github.com/user-attachments/assets/8405a90f-4ea8-4330-9283-de66b10d771d)


**Features** <br>
1. Custom implementation of Generator and Discriminator networks.
2. Visualization of generated images after every training epoch.
3. Training process with detailed logs for loss metrics (Generator and Discriminator).<br>

**Technologies Used** <br>
1. Python
2. PyTorch for neural network implementation.
3. Torchvision for dataset and image utilities.
4. Matplotlib for visualizing generated images.

