# ResNet
[Resnet Paper](https://arxiv.org/abs/1512.03385)

Implementation of the Resnet Paper using Pytorch framework on CIFAR10 and FastAI's Imagenette datasets.

## CIFAR10
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

<img src="https://user-images.githubusercontent.com/27062214/213884752-4dda5b67-9bc2-4500-a273-7bedb6af2b0a.png" alt="drawing" width="600"/>

#### Results:
##### Training Accuracy: 86.86% | Training Loss: 0.3785 | Test Accuracy: 73.66% | Test Loss: 1.1979

### Implemented Architecture Results:
#### Losses:
<img src="https://user-images.githubusercontent.com/27062214/213884961-a17ff50c-3466-40e8-a920-ee3d65d6d548.png" alt="drawing" width="600"/>

#### Predictions:
<img src="https://user-images.githubusercontent.com/27062214/213885481-fe004ff5-cb84-4123-beea-0eb22affcb04.png" alt="drawing" width="600"/>
                                                                                                                                         
## Imagenette
Imagenette is a subset of 10 easily classified classes from Imagenet (tench, English springer, cassette player, chain saw, church, French horn, garbage truck, gas pump, golf ball, parachute).

Created by Jeremy Howard.

#### Results:
##### Training Accuracy: 95.57% | Training Loss: 0.1418 | Test Accuracy: 74.76% | Test Loss: 1.1296

#### [Dataset Git Repo](https://github.com/fastai/imagenette)
<img src="https://user-images.githubusercontent.com/27062214/213885049-2d4fed1e-15cc-4c10-978b-79351e93a890.png" alt="drawing" width="600"/>

#### Losses:
<img src="https://user-images.githubusercontent.com/27062214/213884961-a17ff50c-3466-40e8-a920-ee3d65d6d548.png" alt="drawing" width="600"/>

#### Predictions:
<img src="https://user-images.githubusercontent.com/27062214/213885002-cee6edb4-847f-4f47-bb97-e6e56af7bba9.png" alt="drawing" width="600"/>
