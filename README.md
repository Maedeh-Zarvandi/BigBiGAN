# BigBiGAN-PyTorch

Implementation of [BigBiGAN](https://arxiv.org/abs/1907.02544)

## Architecture
![BigBiGAN](https://github.com/RKorzeniowski/BigBiGAN-PyTorch/blob/main/imgs/bigbigan_arch.png)

<!-- ## Requirements
```
Python 3.6.9
PyTorch 1.6.0
Numpy 1.18.5
``` -->

<!-- ## Implementation -->

### Generator & Discriminator
![BigGAN](https://github.com/RKorzeniowski/BigBiGAN-PyTorch/blob/main/imgs/biggan_arch.jpg)

<!-- Both generator and discriminator follow architecture presented in the [BigGAN](https://arxiv.org/abs/1809.11096) paper  -->

### Encoder

Encoder is implemented as [ResNet](https://arxiv.org/abs/1901.09005) with few fully connected layers on top.

## train 
`python train_gan.py --dataset {supported_dataset} --data_path {path/to/dataset/folder}`

## Datasets
- MNIST 32x32
- FMNIST 32x32
- CIFAR10 32x32
- CIFAR100 32x32
- Imagewoof 64x64
- Imagenette 64x64

<!-- ## Samples -->

### CIFAR10

![CIFAR10](https://github.com/RKorzeniowski/BigBiGAN-PyTorch/blob/main/imgs/CIFAR10_sample.png)

### Imagewoof

![Imagewoof](https://github.com/RKorzeniowski/BigBiGAN-PyTorch/blob/main/imgs/imagewoof_sample.png)

### Evaluation

Evaluated with FID measure and linear classifier accuracy.

<!-- ## Acknowledgments -->
<!-- BigGAN https://github.com/taki0112/BigGAN-Tensorflow -->

<!-- RevNet https://github.com/google/revisiting-self-supervised -->

<!-- Tensorflow implementation of BigBiGAN https://github.com/LEGO999/BigBiGAN-TensorFlow2.0 -->
