# Neural-network-Midterm
<h1 align="center"> Neural-network-Midterm</h1>

GitHub: [https://github.com/Shixu-max/Neural-network-Midtern](https://github.com/Shixu-max/Neural-network-final-term)



## Contents
- [Target](#target)
- [First problem](#first-problem)
  * [Dataset](#dataset)
  * [Data augmentation](#augmentor)
  * [Train models](#train_models)
  * [Compare](#compare)
- [Second problem](#second-problem)
  * [Dataset](#dataset)
  * [Train models](#train-models)
  * [Visualization](#visualization)
  * [Compare](#compare)
- [Third problem](#third-problem)
  * [Pre-processing](#pre-processing)
  * [Train model](#train-model)
- [Packages](#packages)
- [Codes](#codes)


## Target
1 Train and test on CIFAR-100 using CNN network models (ResNet) as baselines; Compare the performance of Cutmix, Cutout, Mixup, and Baseline methods in CIFAR-100 image classification tasks; Visualize three training samples through cutmix, cutout, and mixup, and show a total of 9 images.

2 Train and test the target detection models Faster R-CNN and FCOS on the VOC dataset; Visualize the proposal box of the first stage of Faster R-CNN on four test images; Visualize the detection results (category labels, scores, boundingbox) of three images that are not in the VOC dataset, but contain category objects in the VOC, and compare them. Show a total of six images;
3 Use the Neural Radiance Fields (NeRF) model to conduct 3-D reconstruction of our own photos.
### First problem
Classification task with different data augmentation methods on CIFAR-100 dataset.
#### Dataset
CIFAR-100

https://www.cs.toronto.edu/~kriz/cifar.html


#### Source codes
Source codes and more detials for task 1 can be accessed in `task1`.



### Second problem
Object detection with Faster R-CNN and FCOS
#### Dataset
VOC 2007 
http://host.robots.ox.ac.uk/pascal/VOC/
### Third problem
3-D reconstruction of our own photos with NeRF

## Pre-processing
Use COLMAP and LLFF pre-process the datasets.


COLMAP: You can download it in https://demuc.de/colmap/


LLFF: You can download it in https://gitcode.net/mirrors/fyusion/llff?utm_source=csdn_github_accelerator

## Train model



#### Source codes
Source codes and commands for task 2 are available in `task2/{Model name}`.
