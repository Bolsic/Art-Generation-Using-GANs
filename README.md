# Art-Generation-Using-GANs
Comparison of three GAN architectures on the task of generating paintings

The project was done as a part of the PFE summer camp in 2021. It was done in a pair by Vladan Baišić and Zlata Stefanović. From start to finish, the project took 14 days.

The task was to compare three different generative adversarial network (GAN) architectures that were trained on the database of paintings. The architectures that were used were:

1. Deep Convolutional Generative Adversarial Network (DCGAN)
2. Wasserstein Generative Adverserial Network (WGAN)
3. Spectral Normalization Generative Adverserial Network (SNGAN)


The dataset that was used is the Painter by Numbers dataset. Only paintings tagged as landscape or portrait were used in training.

https://www.kaggle.com/competitions/painter-by-numbers/overview

The landscapes were preprocessed by resizing the image to the 64x64 resolution.

The portraits were preprocessed by detecting the face using OpenCV, cropping the image around the face, and then resizing it to the 64x64 resolution.