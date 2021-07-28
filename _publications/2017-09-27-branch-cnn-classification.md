---
title: "B-CNN: Branch Convolutional Neural Network for Hierarchical Classification"
collection: publications
permalink: /publication/2017-09-27-branch-cnn-classification
excerpt: 'In this paper, we introduce a variant of the traditional CNN model 
          named the Branch Convolutional Neural Network (B-CNN). A B-CNN 
          model outputs multiple predictions ordered from coarse to fine 
          along the concatenated convolutional layers corresponding to the 
          hierarchical structure of the target classes, which can be regarded 
          as a form of prior knowledge on the output.'
date: 2017-09-27
venue: 'arXiv pre-print'
authors: 'Xinqi Zhu, Michael Bain'
---
## Abstract

Convolutional Neural Network (CNN) image classifiers are traditionally 
designed to have sequential convolutional layers with a single output layer. 
This is based on the assumption that all target classes should be treated 
equally and exclusively. However, some classes can be more difficult to 
distinguish than others, and classes may be organized in a hierarchy of 
categories. At the same time, a CNN is designed to learn internal 
representations that abstract from the input data based on its 
hierarchical layered structure. So it is natural to ask if an inverse of 
this idea can be applied to learn a model that can predict over a 
classification hierarchy using multiple output layers in decreasing order of 
class abstraction. In this paper, we introduce a variant of the 
traditional CNN model named the Branch Convolutional Neural Network (B-CNN). 
A B-CNN model outputs multiple predictions ordered from coarse to fine 
along the concatenated convolutional layers corresponding to the hierarchical 
structure of the target classes, which can be regarded as a form of prior 
knowledge on the output. To learn with B-CNNs a novel training strategy, 
named the Branch Training strategy (BT-strategy), is introduced which 
balances the strictness of the prior with the freedom to adjust parameters 
on the output layers to minimize the loss. In this way we show that CNN 
based models can be forced to learn successively coarse to fine concepts 
in the internal layers at the output stage, and that hierarchical prior 
knowledge can be adopted to boost CNN models' classification performance. 
Our models are evaluated to show that the B-CNN extensions improve over the 
corresponding baseline CNN on the benchmark datasets MNIST, CIFAR-10 and 
CIFAR-100.

## Model Architecture

![architecture](https://github.com/zhuxinqimac/B-CNN/blob/master/imgs/arXiv17_architecture.png?raw=true)

## Links

[Paper](https://arxiv.org/abs/1709.09890)

[Code](https://github.com/zhuxinqimac/B-CNN)

## Citation
```
@article{DBLP:journals/corr/abs-1709-09890,
  author    = {Xinqi Zhu and Michael Bain},
  title     = {{B-CNN:} Branch Convolutional Neural Network for Hierarchical Classification},
  journal   = {CoRR},
  volume    = {abs/1709.09890},
  year      = {2017},
  url       = {http://arxiv.org/abs/1709.09890},
  archivePrefix = {arXiv},
  eprint    = {1709.09890},
  timestamp = {Mon, 13 Aug 2018 16:48:54 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-1709-09890.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```
