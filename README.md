# FaceGeneration-DeepConvolutionalNeuralNetworks

As a part of this project, non existing set of faces were generated with the use of an existing dataset. Generation and Classification of faces were carried out with the help of simple Convolutional Neural Network where a GAN model was trained and tested by passing a number of generated random latent vectors to produce new face images. 
K-Means clustering method was used to produce clusters of images depending on selected facial attributes.

Initially the GAN model was trained using the MNIST dataset and then the celebA dataset was used to test and achieve the results.

The celebA dataset consists of 200k images with more than 40 different facial attributes of celebrities such as brown hair, are smiling, wearing glasses, etc. 

GANs, in general, can be defined as a generative model that lets us generate a whole image in parallel. Along with several other kinds of generative models, GANs uses a differentiable function represented by a neural network as a Generator Network.

CLASSIFICATION AND GENERATION OF FACES
The core to the DCGAN architecture uses a standard CNN architecture on the discriminative model. For the generator, convolutions are replaced with upconvolutions, so the representation at each layer of the generator is actually successively larger, as it maps from a low-dimensional latent vector onto a high-dimensional image.

Steps followed for face generation and classification
1. Downloading the dataset - Kaggle - CelebA dataset
2. Preprocessing the data - cutting the original image into 28*28 so that the features were easily selected
3. Creating a GAN model which consists of generator and discriminator 
4. Initialising weights of the networks
5. Train the model - this was done with the help of MNIST dataset
6. Calculate loss functions  
7. Test the model
8. Display results

K-MEANS CLUSTERING
Clusters data by trying to separate samples into n groups of equal variance, thereby decreasing the average squared distance between points in the same cluster. This algorithm requires the number of clusters to be mentioned as an input parameter. It scales well to large number of samples.
