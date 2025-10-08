---
title: "Pluggable Style Representation Learning for Multi-Style Transfer"
collection: publications
category: conferences
excerpt: "**Hongda Liu**, Longguang Wang, Weijun Guan, Ye Zhang, Yulan Guo
**ACCV 2024**<br/><img src='/images/SaMST.png'>"
date: 2024-12-01
venue: 'Asian Conference on Computer Vision (ACCV), Hanoi, Vietnam'
paperurl: 'https://openaccess.thecvf.com/content/ACCV2024/html/Liu_Pluggable_Style_Representation_Learning_for_Multi-Style_Transfer_ACCV_2024_paper.html'
---

Due to the high diversity of image styles, the scalability to various styles plays a critical role in real-world applications. To accommodate a large amount of styles, previous multi-style transfer approaches rely on enlarging the model size while arbitrary-style transfer methods utilize heavy backbones. However, the additional computational cost introduced by more model parameters hinders these methods to be deployed on resource-limited devices. To address this challenge, in this paper, we develop a style transfer framework by decoupling the style modeling and transferring. Specifically, for style modeling, we propose a style representation learning scheme to encode the style information into a compact representation. Then, for style transferring, we develop a style-aware multi-style transfer network (SaMST) to adapt to diverse styles using pluggable style representations. In this way, our framework is able to accommodate diverse image styles in the learned style representations without introducing additional overhead during inference, thereby maintaining efficiency. Experiments show that our style representation can extract accurate style information. Moreover, qualitative and quantitative results demonstrate that our method achieves state-of-the-art performance in terms of both accuracy and efficiency. The codes are available in [[SaMST codes](https://github.com/Chernobyllight/SaMST)]
