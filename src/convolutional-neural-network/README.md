## Convolutional Neural Networks in Pytorch

For this lab, you need to have some ground understanding of pytorch, and basics introduction is available [here](https://pytorch.org/tutorials/beginner/basics/intro.html).

```math
$\newcommand{\underbr}[2]{\underbrace{#1}_{\scriptscriptstyle{#2}}}$
```

### Objective

We want to implement `Convolutional Neural Networks` (CNNs) to classify correctly images for the [CIFAR10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html).

The CIFAR-10 dataset consists of 60 000 32x32 colour images in 10 classes, with 6 000 images per class. There are 50 000 training images and 10 000 test images.

We will first design a custom made CNN using Pytorch to make the classification and then use an architecture available from torchvision that we will either train from scratch or finetune.

We will compare the accuracy on the test set for all networks.

Finally, we will also make use of Data Augmentation to further improve the generalization of our custom model to the testing data.

