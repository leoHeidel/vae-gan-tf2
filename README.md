# vae-gan-tf2
Tensorflow 2 implementation of VEA-GAN 

## Objective:

Implementation of: 
**Autoencoding beyond pixels using a learned similarity metric** by Anders Boesen Lindbo Larsen and Søren Kaae Sønderby and Hugo Larochelle and Ole Winther
https://arxiv.org/abs/1512.09300

Using the GAN loss of: 
**Wasserstein GAN** by Martin Arjovsky and Soumith Chintala and Léon Bottou
https://arxiv.org/abs/1701.07875

## Status:
* The vae part seems to be working.
* The gan part is not working, not giving much improvement to the generated images:
  * Need to balance the different losses
  * Check the discriminator is well implemented, especially the weight cliping part.
