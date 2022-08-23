1] VAEs

# ImgGenVAE: What is this project ?

The basic purpose of this project is to combine my theoretical knowledge of Variational Autoencoders (vae) and Tensorflow to build a VAE from scratch for the task of dataset generation.

# What dataset and libraries are used ?

This project makes use of Tensorflow and Keras Functional API for developing the VAE. Other than this, the OS and Pickle libraries are used for loading and saving
the model as well as creating folders as needed. The "Fashion Mnist" dataset is used to train this specific model.

# How to use this program ?

Just download the ImgGenVAE.ipynb file and ensure that you have an Nvidia GPU available with cuDNN installed on your local system. Just run all the files to train the
model on the fashion mnist dataset. Other image datasets such as Cifar-10, Cifar-100, Regular Mnist can also be used for training the model based on individual goals.

# Future Development ?

Currently, this VAE has a fairly good distribution as seen in the image in the code cell and it does create fairly good images of all the classes in the fashion_mnist
dataset. To further develop this project, I'm going to work on hyperparameter tuning and adding Batchnormalization layer, as well as a Dropout layer to see if I 
can improve the distribution of points in the latent space as represented on the graph.

2] GAN

# GAN: What is this project ?

The basic purpose of this project is to combine my existing knowledge of Variational Autoencoders (VAE), Generative Adversarial Network (GAN),and Tensorflow to 
build a GAN from scratch for the task of dataset generation. The primary focus of this project is on Image Datasets.

# What dataset and libraries are used ?

This project makes use of Tensorflow and Keras Sequential API for developing the GAN. Other than this, the OS and Pickle libraries are used for loading and saving
the model as well as creating folders as needed. The "Fashion Mnist" dataset is used to train this specific model.

# How to use this program ?

Just download the Generative_Adversarial_Networks.ipynb file and ensure that you have an Nvidia GPU available with cuDNN installed on your local system. 
Just run all the files to train the model on the fashion mnist dataset. Other image datasets such as Cifar-10, Cifar-100, Regular Mnist can also be used 
for training the model based on individual goals.

# Future Development ?

Currently, this GAN suffers from a serious "mode collapse" issue and quality of the generated images has a lot of room for improvement. My current goal is to improve my 
theoretical knowledge of GANs, learn about Wasserstein loss and implement that loss function in my GAN to handle the mode collapse issue and work on hyperparameter
tuning to improve the quality of my generated images.

