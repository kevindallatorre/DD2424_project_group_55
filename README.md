# Deep-Learning
This is a repo for the project of [DD2424 Deep Learning in Data Science](https://www.kth.se/social/course/DD2424/) at KTH 2019. 

| Author            | GitHub                                                  |
|:------------------|:--------------------------------------------------------|
| Kevin Dalla Torre | [kevindallatorre](https://github.com/kevindallatorre)   |
| Laura Cros        | [lcrosvila](https://github.com/lcrosvila)               |
| Sena Soyleyici    | [senasoyleyici](https://github.com/senasoyleyici)       |

## Abstract
 This project covers the re-implementation of the paper "Unsupervised Representation Learning by Predicting Image Rotations"(https://arxiv.org/abs/1803.07728), in which the Network in Network (NIN) architecture was used for training. In the paper, a self-supervised learning approach was proposed in which the images were rotated and used for rotation prediction during training, to extract semantic features without requiring manual annotation. Those learned features were then used by means of transfer learning to classify images. In addition to this paper we experimented with a network that used the learned features to predict the bounding box of traffic signs in images. The network and algorithm were implemented in Keras. The results of the experiments showed that the self-supervised approach to extracting features does help to obtain a good representation of the images that can be used in other tasks such as classification or regression.

## Datasets
* [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)

* [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset)

## Contents
* 
