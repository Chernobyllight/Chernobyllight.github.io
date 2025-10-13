---
title: "Preserving Full Degradation Details for Blind Image Super-Resolution"
collection: publications
category: conferences
excerpt: "**Hongda Liu**, Longguang Wang, Ye Zhang, Kaiwen Xue, Shunbo Zhou, Yulan Guo<br />**<font color=red>Arxiv 2024</font>**<br/><img src='/images/ReDSR.png'>"
date: 2024-03-01
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2407.01299'
---
The performance of image super-resolution relies heavily on the accuracy of degradation information, especially under blind settings. Due to the absence of true degradation models in real-world scenarios, previous methods learn distinct representations by distinguishing different degradations in a batch. However, the most significant degradation differences may provide shortcuts for the learning of representations such that subtle difference may be discarded. In this paper, we propose an alternative to learn degradation representations through reproducing degraded low-resolution (LR) images. By guiding the degrader to reconstruct input LR images, full degradation information can be encoded into the representations. In addition, we develop a distribution alignment loss to facilitate the learning of the degradation representations by introducing a bounded constraint. Moreover, to achieve larger receptive fields to capture information from a wider region for better restoration results, we introduce a degradation-aware Mamba module to efficiently model long-range dependency between the anchor pixel and the surrounding informative pixels. And the module strikes a flexible adaption to various degradations based on the learned representations. Experiments show that our representations can extract accurate and highly robust degradation information. Evaluations on both synthetic and real images demonstrate that our ReDSR achieves state-of-the-art performance for the blind SR tasks.
