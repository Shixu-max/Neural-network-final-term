# Neural-network-final-term
<h1 align="center"> Neural-network-finalterm</h1>

GitHub: [[https://github.com/Shixu-max/Neural-network-final-term](https://github.com/Shixu-max/Neural-network-final-term)]



## Contents
- [Target](#target)
- [First problem](#first-problem)
  * [Dataset](#dataset)
  * [Source codes](#codes1)
- [Second problem](#second-problem)
  * [Dataset](#dataset)
  * [Source_codes](#compare)
- [Third problem](#third-problem)
  * [Pre-processing](#pre-processing)
  * [Train model](#train-model)
- [Packages](#packages)
- [Codes](#codes)


## Target
1 Pretrain ResNet-18 with SimCLR, a self-supervised learning strategy on STL10 dataset; Validate effectiveness of self-supervised learning with classification performance on CIFAR-100 (linear classification protocol & supervised learning with and w/o SimCLR pretrained) 

2 Train and test the target detection models Faster R-CNN and FCOS on the VOC dataset; Visualize the proposal box of the first stage of Faster R-CNN on four test images; Visualize the detection results (category labels, scores, boundingbox) of three images that are not in the VOC dataset, but contain category objects in the VOC, and compare them. Show a total of six images;

3 Use the Neural Radiance Fields (NeRF) model to conduct 3-D reconstruction of our own photos.
### First problem
Comparisons of classification performance with & w/o self-supervised learning.

#### Dataset

- STL-10 https://cs.stanford.edu/~acoates/stl10/ 

- CIFAR-100 https://www.cs.toronto.edu/~kriz/cifar.html

#### Source codes

Source codes and more details for task 1 can be accessed in `task1`.



### Second problem
Use the vision transformer to train on the CIFAR-100 dataset from scratch. The vision transformer is handcrafted.
#### Dataset
In this experiment, we choose the CIFAR-100 dataset to experiment on. It contains 50,000 natural images in the training dataset while 10,000 for testing. Each of them is of size 32 x 32, categorized in one of the 100 classes.

https://www.cs.toronto.edu/~kriz/cifar.html

#### Source codes

Source codes and more details for task 2 can be accessed in `task2`.
### Third problem
3-D reconstruction of our own photos with NeRF

## Pre-processing
Use COLMAP and LLFF pre-process the datasets.


COLMAP: You can download it in https://demuc.de/colmap/


LLFF: You can download it in https://gitcode.net/mirrors/fyusion/llff?utm_source=csdn_github_accelerator

## Train model
Use git bush or anaconda prompt, run: python run_nerf.py --config configs/bottle.txt or toy.txt


NeRF-PyTorch: You can download the nerf-pytorch model in https://gitcode.net/mirrors/yenchenlin/nerf-pytorch?utm_source=csdn_github_accelerator


Train results can be found in task 3/toy_test and bottle_test.

### Packages
Numpy, PyTorch with cuda, etc. in requirement.txt of LLFF and NeRF-PyTorch.


#### Source codes
Source codes and commands for task 3 are available in 

https://gitcode.net/mirrors/fyusion/llff?utm_source=csdn_github_accelerator

https://gitcode.net/mirrors/yenchenlin/nerf-pytorch?utm_source=csdn_github_accelerator


