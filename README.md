# Generative-Adversarial-Networks

A generative adversarial network (GAN) is a class of machine learning frameworks designed by Ian Goodfellow and his colleagues in June 2014. Two neural networks contest with each other in a game (in the form of a zero-sum game, where one agent's gain is another agent's loss).

Given a training set, this technique learns to generate new data with the same statistics as the training set. For example, a GAN trained on photographs can generate new photographs that look at least superficially authentic to human observers, having many realistic characteristics. Though originally proposed as a form of generative model for unsupervised learning, GANs have also proved useful for semi-supervised learning, fully supervised learning, and reinforcement learning.

The core idea of a GAN is based on the "indirect" training through the discriminator,[clarification needed] which itself is also being updated dynamically. This basically means that the generator is not trained to minimize the distance to a specific image, but rather to fool the discriminator. This enables the model to learn in an unsupervised manner.

1. Two Data sets are used in this project separately to Generate new synthetic images 1. mnist data set 2. chest x ray data set consisting of two classes (normal, pneumonia) https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
2. The quality of the synthetic images generated after training GAN was acceptable and approved by data scientist
