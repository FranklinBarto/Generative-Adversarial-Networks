# Introduction

## Generative Adversarial Networks (GANs) on Fashion MNIST

Generative Adversarial Networks (GANs) have revolutionized the field of artificial intelligence by enabling the generation of realistic synthetic data. In this notebook, we will explore the application of GANs to the Fashion MNIST dataset, which consists of grayscale images of various clothing items such as shirts, pants, shoes, and more.

## Objectives

The main objectives of this notebook are:

1. **Understand GAN Architecture**: which consist of a generator and a discriminator. The generator aims to create realistic images, while the discriminator attempts to distinguish between real and generated images.
2. **Implement a GAN**: building and training the generator and discriminator networks.
3. **Train the GAN**: To train the GAN on the Fashion MNIST dataset. We will monitor the training process, including the losses of both the generator and discriminator, and adjust hyperparameters as necessary.
4. **Generate Fashion Images**: We will visualize and evaluate the quality of these synthetic images.
5. **Analyze Results**: To analyze the results and understand the strengths and limitations of our GAN model. We will discuss potential improvements and future directions for research.

## Dataset

The Fashion MNIST dataset is a large collection of 28x28 grayscale images, each labeled with one of ten categories representing different types of clothing and accessories. Each image is a low-resolution representation of a fashion item, making it a suitable challenge for a quick implementation of a generative model.

## Model
The model is built using tensoflow notably with LeakyReLU, Dropout,  BatchNormalization and Convolution layers