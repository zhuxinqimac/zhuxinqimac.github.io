---
title: "Where and What? Examining Interpretable Disentangled Representations"
collection: publications
permalink: /publication/2021-03-01-where-and-what
excerpt: 'Unlike the independence assumption,
          interpretability has rarely been exploited to encourage disentanglement
          in the unsupervised setting. In this paper, we examine the interpretability
          of disentangled representations by investigating two questions:
          where to be interpreted and what to be interpreted?'
date: 2021-03-01
venue: 'Conference on Computer Vision and Pattern Recognition 2021 (Oral, Best Paper Candidate)'
paperurl: 'https://arxiv.org/abs/2104.05622'
---

## Disentangled Semantic Variations on FFHQ Dataset
![trav_animation](https://github.com/zhuxinqimac/PS-SC/blob/main/imgs/traversals.gif?raw=true)

## Abstract

Capturing interpretable variations has long been one of the goals in
disentanglement learning. However, unlike the independence assumption,
interpretability has rarely been exploited to encourage disentanglement
in the unsupervised setting. In this paper, we examine the interpretability
of disentangled representations by investigating two questions:
where to be interpreted and what to be interpreted? A latent code is
easily to be interpreted if it would consistently impact a certain subarea
of the resulting generated image. We thus propose to learn a spatial mask
to localize the effect of each individual latent dimension. On the other
hand, interpretability usually comes from latent dimensions that capture
simple and basic variations in data. We thus impose a perturbation on a
certain dimension of the latent code, and expect to identify the
perturbation along this dimension from the generated images so that
the encoding of simple variations can be enforced. Additionally, we develop
an unsupervised model selection method, which accumulates perceptual
distance scores along axes in the latent space. On various datasets,
our models can learn high-quality disentangled representations without
supervision, showing the proposed modeling of interpretability is an
effective proxy for achieving unsupervised disentanglement.

## Video Presentation
[![where-and-what](../files/cvpr21-video-thumbnail.png)](https://youtu.be/iXAs2GnDp7g")

## Links

[Paper](https://arxiv.org/abs/2104.05622)

[Supplementary](../files/cvpr21_supp.pdf)

[Code](https://github.com/zhuxinqimac/PS-SC)

## Citation
```
@inproceedings{Xinqi_cvpr21,
author={Xinqi Zhu and Chang Xu and Dacheng Tao},
title={Where and What? Examining Interpretable Disentangled Representations},
booktitle={CVPR},
year={2021}
}
```
