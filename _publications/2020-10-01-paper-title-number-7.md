---
title: "Densely connected GCN model for motion prediction"
date: 2020-11-01
venue: 'CASA'
---

[Download paper here](https://onlinelibrary.wiley.com/doi/full/10.1002/cav.1958)

Authors: Yanran Li, Lingteng Qiu, Li Wang, Fangde Liu, Zhao Wang, Sebastian Iulian Poiana, Xiaosong Yang and Jianjun Zhang. 

Abstract: Human motion prediction is a fundamental problem in understanding human natural movements. This task is very challenging due to the complex human body constraints and diversity of action types. Due to the human body being a natural graph, graph convolutional network (GCN)-based models perform better than the traditional recurrent neural network (RNN)-based models on modeling the natural spatial and temporal dependencies lying in the motion data. In this paper, we develop the GCN-based models further by adding densely connected links to increase their feature utilizations and address oversmoothing problem. More specifically, the GCN block is used to learn the spatial relationships between the nodes and each feature map of the GCN block propagates directly to every following block as input rather than residual linked. In this way, the spatial dependency of human motion data is exploited more sufficiently and the features of different level of scale are fused more efficiently. Extensive experiments demonstrate our model achieving the state-of-the-art results on CMU dataset.