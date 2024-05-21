---
date: 2023-02-09
title: "Drought stress prediction and propagation using time series modeling on multimodal plant image sequences"
permalink: /publication/2023-drought-stress/
excerpt: "The paper introduces two novel algorithms for predicting and propagating drought stress in plants using image sequences captured by cameras in two modalities, i.e., visible light and hyperspectral."
citation: "Das Choudhury, S.<sup>`*`</sup>, **Saha, S.**<sup>`*`</sup>, Samal, A., Mazis, A. and Awada, T."
paperurl: "https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2023.1003150/full"
venue: "Frontiers in Plant Science, 14, p.1003150"
imgsrc: "/assets/pub/images/2023-drought-stress.png"
author_profile: true
---

## Abstract

The paper introduces two novel algorithms for predicting and propagating drought stress in plants using image sequences captured by cameras in two modalities, i.e., visible light and hyperspectral. The first algorithm, VisStressPredict, computes a time series of holistic phenotypes, e.g., height, biomass, and size, by analyzing image sequences captured by a visible light camera at discrete time intervals and then adapts dynamic time warping (DTW), a technique for measuring similarity between temporal sequences for dynamic phenotypic analysis, to predict the onset of drought stress. The second algorithm, HyperStressPropagateNet, leverages a deep neural network for temporal stress propagation using hyperspectral imagery. It uses a convolutional neural network to classify the reflectance spectra at individual pixels as either stressed or unstressed to determine the temporal propagation of stress in the plant. A very high correlation between the soil water content, and the percentage of the plant under stress as computed by HyperStressPropagateNet on a given day demonstrates its efficacy. Although VisStressPredict and HyperStressPropagateNet fundamentally differ in their goals and hence in the input image sequences and underlying approaches, the onset of stress as predicted by stress factor curves computed by VisStressPredict correlates extremely well with the day of appearance of stress pixels in the plants as computed by HyperStressPropagateNet. The two algorithms are evaluated on a dataset of image sequences of cotton plants captured in a high throughput plant phenotyping platform. The algorithms may be generalized to any plant species to study the effect of abiotic stresses on sustainable agriculture practices.
