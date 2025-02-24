# Convolutional Neural Networks

- NN architecture primarily used for image recognition and processing tasks
- Able to capture location invariant spacial features i.e. CNNs can extract object properties withing an image irrelative of the its location
- Made of 2 layers
  - **Convolutional Layer:** 
    - A kernel [matrix that extracts the features from image] is placed over image and the weights of the kernel are unknown; found during the training process
    - Kernels in different convolutional layers exract different features based on their kernel weighs

    ***Size of output image is o given as:***

$o = \frac{i + 2p - k}{2} + 1$

where o = output image size; p = padding size; i = input image size; k = size of kernel; s = stride

![The image shows how convolutional layer generates output](images/output_feature_map.png)
***The output generated here is called a feature map***
  - **Pooling Layer:** 
    - Reduces sample size of input
    - Perfoms some sort of aggregating operations say average pooling, max pooling, min pooling etc.
    - Reduces the number of parameters the network will have to deal with

- Architecture of a CNN

![Representation of a general CNN architecture](images/general_arch_CNN.png)

### Types of Convolutional layers

- **Standard Convolutional Layer:** Applies a kernel to extract the features of the image
- **Deconvolutional Layer:** Takes in feature map as the input and preduces the original image i.e. reverses the precess of standard convolutional layer
- **Transposed Convolutional Layer:** Used to perform upsampling of input data i.e. feature map has greater spacial dimensions than that of input feature map
![The image shows how the Transposed Convolutional Layer generates its output](images/transposedCL.png)
    ***Size of output image is o given as:***
$o = (i - 1) \times s + k - 2p$

---

### Deep CNN GANs

- The architecture os Deep CNN GAN is similar to an ordinary GAN except the fact that both adveseries [Generator and Discriminator] are CNNs with some archtectural constrains which help the pair to learn and create better generated images

- [About Deep CNN based GANs in detail](https://arxiv.org/pdf/1511.06434)

- 