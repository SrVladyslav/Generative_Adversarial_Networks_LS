# Generative Adversarial Networks
There are a lot of applications of GANs, but here I will implement some Proof of Concept in order to learn better the base of this networks and practise coding with Pytorch.


## Content
1- GAN-MNIST: GAN implemented with Linear Layers on MNIST dataset
  - Optimizer Discriminator: Adam , learning rate= 0.0002, betas= (0.4, 0.999).
  - Optimizer Generator: Adam , learning rate= 0.0002, betas= (0.4, 0.999).
  - Criterion: Binary Cross Entropy
  - 30 Epochs

2- GAN-CELEBA: Trained Generator to use it on CELEBA dataset, personalized to launch from GAN_GUI.py,
DCGAN explained on < https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html >
