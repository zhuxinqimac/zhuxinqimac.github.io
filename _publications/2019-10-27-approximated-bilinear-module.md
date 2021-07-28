---
title: "Approximated Bilinear Modules for Temporal Modeling"
collection: publications
permalink: /publication/2019-10-27-approximated-bilinear-module
excerpt: 'We consider two less-emphasized temporal properties of video: 
          1. Temporal cues are fine-grained; 2. Temporal modeling needs 
          reasoning. To tackle both problems at once, we exploit approximated 
          bilinear modules (ABMs) for temporal modeling.'
date: 2019-10-27
venue: 'International Conference on Computer Vision'
authors: 'Xinqi Zhu, Chang Xu, Langwen Hui, Cewu Lu, Dacheng Tao'
---
## Abstract

We consider two less-emphasized temporal properties of video: 1. Temporal 
cues are fine-grained; 2. Temporal modeling needs reasoning. To tackle 
both problems at once, we exploit approximated bilinear modules (ABMs) 
for temporal modeling. There are two main points making the modules 
effective: two-layer MLPs can be seen as a constraint approximation 
of bilinear operations, thus can be used to construct deep ABMs in 
existing CNNs while reusing pretrained parameters; frame features can 
be divided into static and dynamic parts because of visual repetition 
in adjacent frames, which enables temporal modeling to be more efficient. 
Multiple ABM variants and implementations are investigated, from high 
performance to high efficiency. Specifically, we show how two-layer subnets 
in CNNs can be converted to temporal bilinear modules by adding an 
auxiliary-branch. Besides, we introduce snippet sampling and shifting 
inference to boost sparse-frame video classification performance. 
Extensive ablation studies are conducted to show the effectiveness of 
proposed techniques. Our models can outperform most state-of-the-art 
methods on Something-Something v1 and v2 datasets without Kinetics 
pretraining, and are also competitive on other YouTube-like action 
recognition datasets.

## Model Architecture

![architecture](https://github.com/zhuxinqimac/abm-pytorch/blob/master/imgs/iccv19_architecture.png?raw=true)

## Links

[Paper](https://arxiv.org/abs/2007.12887)

[Code](https://github.com/zhuxinqimac/abm-pytorch)

## Citation
```
@inproceedings{ABM_iccv19,
author={Xinqi Zhu and Chang Xu and Langwen Hui and Cewu Lu and Dacheng Tao},
title={Approximated Bilinear Modules for Temporal Modeling},
booktitle={ICCV},
year={2019}
}
```
