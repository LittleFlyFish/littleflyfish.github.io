---
title: "MIMO is all you need：A Strong Multi-In-Multi-Out Baseline for Video Prediction"
date: 2023-11-01
venue: 'AAAI'
Authors: Ning, Shuliang and Lan, Mengcheng and Li, Yanran and Chen, Chaofeng and Chen, Qian and Chen, Xunlai and Han, Xiaoguang and Cui, Shuguang
---

[Download paper here](https://arxiv.org/pdf/2212.04655)

Authors: Shuliang Ning, Mengcheng Lan, Yanran Li, Chaofeng Chen, Qian Chen, xunlai chen, Xiaoguang Han, Shuguang Cui.


The mainstream of the existing approaches for video prediction builds up their models based on a Single-In-Single-Out (SISO) architecture, which takes the current frame as input to predict the next frame in a recursive manner. This way often leads to severe performance degradation when they try to extrapolate a longer period of future, thus limiting the practical use of the prediction model. Alternatively, a Multi-In-Multi-Out (MIMO) architecture that outputs all the future frames at one shot naturally breaks the recursive manner and therefore prevents error accumulation. However, only a few MIMO models for video prediction are proposed and they only achieve inferior performance due to the date. The real strength of the MIMO model in this area is not well noticed and is largely under-explored. Motivated by that, we conduct a comprehensive investigation in this paper to thoroughly exploit how far a simple MIMO architecture can go. Surprisingly, our empirical studies reveal that a simple MIMO model can outperform the state-of-the-art work with a large margin much more than expected, especially in dealing with longterm error accumulation. After exploring a number of ways and designs, we propose a new MIMO architecture based on extending the pure Transformer with local spatio-temporal blocks and a new multi-output decoder, namely MIMO-VP, to establish a new standard in video prediction. We evaluate our model in four highly competitive benchmarks (Moving MNIST, Human3.6M, Weather, KITTI). Extensive experiments show that our model wins 1st place on all the benchmarks with remarkable performance gains and surpasses the best SISO model in all aspects including efficiency, quantity, and quality. We believe our model can serve as a new baseline to facilitate the future research of video prediction tasks. The code will be released.