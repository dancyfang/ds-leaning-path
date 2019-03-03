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

Gradient vanishing




