# GAN_From_Scratch

## Purpose
The purpose of this notebook is to show an introductory look into generative adversarial networks (GANs), used extensively within the realm of generative AI to produce novel images based on the underlying distributions of input samples.

The most basic GAN consists of 2 networks:
  1. The generator, $G$, which produces synthesized examples. During training, the goal of the generator is to create examples that become increasingly more "realistic", i.e. as close to the ground truth distribution as possible.
  2. The discriminator, $D$, which judges inputs as real or fake. During training, the goal of the discriminator is to judge the generator's outputs as accurately as possible.
 
 ## Sources
 * *Dataset:* MNIST
 * *Machine Learning with PyTorch and Scikit-Learn.* Raschka, Liu, Mirjalili, Dzhulgakov. Packt Publishing.
