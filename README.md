# Generative_Models_VAE_and_GAN

## Deep Learning 2nd coursework for MSc AI at Imperial College London, academic year 2020-2021

The VAE_GAN.ipynb file is divided in two parts

* The first part consists in a variational autoencoder used in the MINST dataset. In adition to the implementation, the following is shown or discussed
    * Reconstruction samples and a few generated samples are shown
    * How does the loss function relate to the VAE prior, the output data domain, and disentanglement in the latent space
    * Behaviour of the log-likelihood loss and the KL loss by observing their graphs
    * Posterior collapse
    * Role of the KL loss term and 𝛽 in the latent representation of the test set (visualized using T-SNE)
    * Interpolation in the latent space is shown
   
* The second part consists of a Deep Convolutional GAN implementation in the CIFAR-10 dataset. Some important features of the implementation are:
    * Batch normalisation 
    * ReLU activation in the generator, and Leaky ReLU activation in the discriminator
    * Data augmentation - RandomCrop and RandomHorizontalFlip
   
   The following topics were discussed in the second part:
    * Generator and discriminator's loss curves
    * Mode collapse
