# Generative-Adversarial-Networks-GANs-with-MNIST
Built a Generative Adversarial Network (GAN) using Keras and TensorFlow to generate realistic handwritten digits from the MNIST dataset.
## **Overview**
A GAN consists of:
- **Generator**: Creates fake images from random noise
- **Discriminator**: Determines if an image is real (from dataset) or fake (from generator)
The goal was to train both networks together for **30 epochs** and observe how fake digits improve over time.
## **Results & Analysis**
- Generator improved over time: Fake digits started looking more realistic after ~10 epochs
- Discriminator learned to distinguish fake vs. real more sharply at the beginning
- Loss graphs showed healthy competition and learning dynamics between both models
