# Getting started with Deep learning

This repository contains learning material (code and notes) for Deep learning. We focus primilarly on computer vision and time series models. Models are implemented using Tensorflow, Pytorch, and Flux (julia).

Reading Resources

- Different Frameworks

  - [Comparative Study of Deep Learning Software Frameworks](https://arxiv.org/pdf/1511.06435.pdf) (flux missing :cry:)

- Improving architecture

  - [Efficient Deep Learning Book](https://efficientdlbook.com)
  - [Efficient Deep Learning: A Survey on Making Deep Learning Models Smaller, Faster, and Better](https://arxiv.org/abs/2106.08962)

## Computer Vision

### State of art (SOA) Architectures

- [Inception Architecture](notes/inception.md)
- [Common CNN Architectures](notes/common_cnns.md)

### `Code`

#### **Image Classification**
  
  - Classify natural images into 10 categories
    - `Dataset`: CIFAR-10
       - Model 1: (3-layer) Convolution Neural Networks: [![tensorflow - code](https://img.shields.io/badge/tensorflow-code-2ea44f)](models/CIFAR-basic.ipynb)
       - Model 2: With data augmentation and batch normalization: [![tensorflow - code](https://img.shields.io/badge/tensorflow-code-2ea44f)](models/CIFAR_AuBN.ipynb)
  - Classify images of clothing
    - `Dataset`: FashionMNIST
      - Model 1: (3-layer) Convolution Neural Networks: [![tensorflow - code](https://img.shields.io/badge/tensorflow-code-2ea44f)](models/fashionMNIST.ipynb)
      - Model 2: Lenet architecture: [![pytorch - code](https://img.shields.io/badge/pytorch-code-2ea44f)](models/lenet-mnist.ipynb)
  - Identify Blood Cell Subtypes From Images
    - `Dataset` - Blood cell ([kaggle](https://www.kaggle.com/code/paultimothymooney/identify-blood-cell-subtypes-from-images/notebook))
      - Model: Custom-ResNet: [![tensorflow - code](https://img.shields.io/badge/tensorflow-code-2ea44f)](models/ResNet50-CUS.ipynb)

#### **Transfer learning**

  - Extracting image features
     - Model: Extract image features using VGG16 architecture: [![tensorflow - code](https://img.shields.io/badge/tensorflow-code-2ea44f)](models/VGG16.ipynb)
  - Image classification
    - `Dataset`: Fruit-360 ([kaggle](https://www.kaggle.com/moltean/fruits))
      - Model: ResNet-50: [![tensorflow - code](https://img.shields.io/badge/tensorflow-code-2ea44f)](models/Resnet50.ipynb)

#### **Generative Adveserial Network**

  - `Dataset`: MNIST
    - Generate Hand written digits: [![tensorflow - code](https://img.shields.io/badge/pytorch-code-2ea44f)](models/dcgan.ipynb)


you can also check out my solutions for [Advance Tensorlfow Specialization Course](https://github.com/ssaket/coursera-advance-tensorflow-techniques) 

## Time Series

### Reading Resources

#### **Parametric methods**
- In this approach, the task is to estimate the parameters of the model that describes the stochastic process.

#### **Non Parametric methods**
- In this approach, we explicitly estimate the covariance or the spectrum of the process without assuming that the process has any particular structure.

#### **Time Series Comparision**
- [Dynamic time wraping (DTW)](notes/dynamic-time-wraping.md)

- [Euclidian comparision](notes/euclidian.md)

### Code

- `Naive Forecast`: [julia-code/naive-forcasting.jl](julia-code/naive-forcasting.jl)
