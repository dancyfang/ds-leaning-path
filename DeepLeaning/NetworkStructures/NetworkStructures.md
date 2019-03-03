# A Gallary of Deeep Learning Network Structures

## 1. CNN
When doing image recognition, the size of input could easily get extremely large (n*n*3). Using fully connected (FC) layers in this case will cause the number of
parameters to spike. Luckily, Convolutional Neural Network(CNN) is a structure designed for this kind of problems.

![convolution]()

### 1) advantages
a. Fewer parameters than Fully Connect network

By using the filter to swipe across the input and convolute with each part of it, CNN uses a more efficient way than fully connected network
to multiply weights to the input. The filter connects the input locally, and parameters are shared across all the input region.

b. Robust to transformation

Transformations of the input will have little impact on the effectiveness of CNN.

### 2) basic concepts
a. convolution

b. padding

c. strided convolution

d. choice of activation functions

e. pooling

### 3) popular networks
a. LeNet

![LeNet]()

7 layers including: convolutional, pooling and FC.

b. AlexNet

![AlexNet]()

c. GoogleNet(Inception Net)

![GoogleNet]()

Inception: stack the outputs of multiple filters at the same level. Solves the issue of uncertainty in kernal size. 1 * 1 filter is used to reduce the number of channels.

d. ResNet

![ResNet]()

Gradient vanishing / exploding: As we do backpropagation, the more layers we have, the more gradient terms we have to multiply on the gradients of the parameters. If those gradient terms are smaller than 1, we could have gradient vanishing problem. Otherwise, if larger than 1, gradient exploding may happen.

Residual Neural Network creates some shortcuts in the structure, which solves the gradient vanishing/exploding problem of very deep NN.

DenseNet is a variation of ResNet. At each layer, there are shortcuts connecting outputs from all previous layers to the current layer's input.

![DenseNet]()

## 2. RNN


## 3. Unsupervised learning structures

### 1) Autoencoder

Autoencoder network is comprised of the encoder phase and the decoder phase. In the encoder phase, the network learns a representation of the input by shrinking the size of input and keeping only important information. In the decoder phase, the network enriches the output of the input phase and expand it to the orignial input size.

![Autoencoder]()

### 2) GANs

### 3) Deep Belief Networks






