# Introduction

Tips and tricks of Deep learning

## Resources

Improving architecture

- [Efficient Deep Learning Book](https://efficientdlbook.com)
- [Efficient Deep Learning: A Survey on Making Deep Learning Models Smaller, Faster, and Better](https://arxiv.org/abs/2106.08962)

## Vision Models

### Architectures

- [Inception Architecture](blogs/inception.md)

- [Common CNN Architectures](blogs/common_cnns.md)

### Sample Deep learning Models Examples

1. [`CIFAR_AuBN.ipynb`](models/CIFAR_AuBN.ipynb) : CIFAR with Data Augumentation and Batch Normalization.
2. [`CIFAR-basic.ipynb`](models/CIFAR-basic.ipynb): Plain old CIFAR
3. [`fashionMNIST.ipynb`](models/fashionMNIST.ipynb): Plain CNN network for classification task.
4. [`lenet-mnist.ipynb`](models/lenet-mnist.ipynb): LeNet architecture in pytorch
5. [`VGG16.ipynb`](models/VGG16.ipynb): Feature selection and gain some insights

## Time Series Models

Imperical and Deep learning algorithms for time series analysis and forecasting.

**Parametric methods**, in this approach, the task is to estimate the parameters of the model that describes the stochastic process.

**Non Parametric methods**, this approach explicitly estimate the covariance or the spectrum of the process without assuming that the process has any particular structure.

## Models

- `Naive Forecast`: [julia-code/naive-forcasting.jl](julia-code/naive-forcasting.jl)

## Comparision

- [`Dynamic time wraping (DTW)`](notes/dynamic-time-wraping.md)

- [`Euclidian`](notes/euclidian.md)
