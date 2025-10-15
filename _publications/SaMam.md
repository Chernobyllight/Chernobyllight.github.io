---
title: "SaMam: Style-aware State Space Model for Arbitrary Image Style Transfer"
collection: publications
category: conferences
excerpt: "<em>**Hongda Liu**, Longguang Wang, Ye Zhang, Ziru Yu, Yulan Guo</em><br />**<font color=red>CVPR 2025 Highlight</font>**<br/><img src='/images/samam2.png'>"
date: 2025-06-01
venue: 'Conference on Computer Vision and Pattern Recognition (CVPR), Nashville, Tennessee, America'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2025/html/Liu_SaMam_Style-aware_State_Space_Model_for_Arbitrary_Image_Style_Transfer_CVPR_2025_paper.html'
---
Global effective receptive field plays a crucial role for image style transfer (ST) to obtain high-quality stylized results. However, existing ST backbones (e.g., CNNs and Transformers) suffer huge computational complexity to achieve global receptive fields. Recently, State Space Model (SSM), especially the improved variant Mamba, has shown great potential for long-range dependency modeling with linear complexity, which offers an approach to resolve the above dilemma. In this paper, we develop a Mamba-based style transfer framework, termed SaMam. Specifically, a mamba encoder is designed to efficiently extract content and style information. In addition, a style-aware mamba decoder is developed to flexibly adapt to various styles. Moreover, to address the problems of local pixel forgetting, channel redundancy and spatial discontinuity of existing SSMs, we introduce local enhancement and zigzag scan mechanisms. Qualitative and quantitative results demonstrate that our SaMam outperforms state-of-the-art methods in terms of both accuracy and efficiency. The codes are available in [[SaMam codes](https://github.com/Chernobyllight/SaMam)].
