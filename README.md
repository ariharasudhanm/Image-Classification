# Image classification using CNN in Pytorch 

## About / Synopsis

* This is a model that is used for classificiation of Numbers from  0 to 9 created using convolutional neural networks in Pytorch.
* Project status: working/Model is getting optimized for the best performance


## Table of contents

> * [Title / Repository Name](#title--repository-name)
>   * [About / Synopsis](#about--synopsis)
>   * [Table of contents](#table-of-contents)
>   * [Implementation](#implementation)
>   * [Usage](#usage)
>     * [Features](#features)
>     * [Content](#content)
>     * [Requirements](#requirements)
>     * [Limitations](#limitations)


## Implementation

Model is trained for the best accuracy and it can be used with the sample batch of data with images of size (1,28,28) as np.ndarray converted to tensors.

## Usage
It is used to classify images from 0 to 9.
It can identify images of complex forms and irregular shapes.

### Features
* Usually image classification is traines using neural networks but in order to identify the images of complex forms and improper shapes, since CNN can surplus   amount of features and match it all over end to end of an image.

* It is trained using Adadelta optimizer to get the better accuracy since it restricts the large scale of past accumaulted gradients and doesn't requires a default learning rate.

### Content
Trained model is trained with batch size of 10 so the final accuracy can further be increased to a certain level depending on the optimizer.

### Requirements
It requires minimum of the following versions to run the file.
 * jupyter version -->> 1.0.0
 * torch version -->> 1.4.0
 * torchvision -->> 0.5.0
 * matplotlib version -->> 3.1.2

Optional requirements to view the images 
 * numpy -->> 1.20.3 
 * PIL 1.1. 7


### Limitations
Images with two consecutive numbers cannot be calssified and requires network to be optimized accordingly currently it needs batch data of images and tensors of values ranging from 0 to 9 but currently working on model to use handwritten data as a input.
