# Autoencoders

## Getting Started
This repo lists the attempts at exploring autoencoders, both dense and convolutional, for the independent project in summer of 2017.

## File Structure
The files in the repo are as follows:

``autoencoder.py`` Trains a convolutional autoencoder.
``denoising_autoencoder.py`` Trains a denoising autoencoder.
``dense_vae.py`` Trains a fully connected conditional variational autoencoder.
``conv_vae.py`` Trains a convolutional conditional variational autoencoder.
``conv_vae_light.py`` Trains a convolutional conditional variational autoencoder, with fewer parameters.

``manifold_script.py`` provides two functions. One to display the 2D manifold learned by the model and another to generate images given an input string. 
``main_file.py`` is the demo script that uses the above functions.

## Requirements
- Keras 
- TensorFlow 
- Theano
