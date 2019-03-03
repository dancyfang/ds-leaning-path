# A Gallary of Deeep Learning Network Structures

## 1. CNN
When doing image recognition, the size of input could easily get extremely large (n*n*3). Using fully connected layers in this case will cause the number of
parameters to spike. Luckily, Convolutional Neural Network(CNN) is a structure designed for this kind of problems.

pic

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
