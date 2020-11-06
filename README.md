# General Adversarial Networks (GAN)
Using a GAN implemented with Keras to generate images similar to the MNIST Dataset

## What are GANs?
Generative adversarial networks (GANs) are a type of deep neural network used to generate synthetic images. The architecture comprises two deep neural networks, a generator and a discriminator, which work against each other (thus, “adversarial”). The generator generates new data instances, while the discriminator evaluates the data for authenticity and decides whether each instance of data is “real” from the training dataset, or “fake” from the generator.

Together, the generator and discriminator are trained to work against each other until the generator is able to create realistic synthetic data that the discriminator can no longer determine is fake. After successful training, the data produced by the generator can be used to create new synthetic data, for potential use as input to other deep neural networks. [Read More](https://in.mathworks.com/discovery/generative-adversarial-networks.html)

## Dataset Used
Dataset used is the popular MNIST Digit dataset. The dataset is pre-loaded into the keras library and can be used by importing it from keras.

## Results
The following is a set of 25 images produced by the GAN after 40000 epochs:


Epoch wise images produced by the GAN are stored in the folder 'gan_images'.
