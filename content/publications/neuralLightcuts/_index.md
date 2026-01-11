---
title: "Neural Importance Sampling of Many Lights"
date: "2025-08-12"
draft: false
layout: "custom-publication"
description: | 
    *Neural approach for estimating spatially varying light selection distributions to improve importance sampling in Monte Carlo rendering.*<br>
    [Pedro Figueiredo](https://pedrovfigueiredo.github.io/), **Qihao He**, [Steve Bako](https://web.ece.ucsb.edu/~sbako/), [Nima Khademi Kalantari](https://people.engr.tamu.edu/nimak/index.html)<br>
    ACM SIGGRAPH 2025 (Conference Track) <br>
    [Paper](/publications/nis_manylight.pdf) | [Code](https://github.com/pedrovfigueiredo/nis-manylights)

# pdf: "paper.pdf"
# arxiv: "https://arxiv.org/abs/2025.xxxxx"
# video: "https://www.youtube.com/watch?v=xxxxx"
code: "https://github.com/pedrovfigueiredo/nis-manylights"
project: "https://pedrovfigueiredo.github.io/projects/manylights/SIGGRAPH_2025_Importance_Sampling/index.html"
redirect: "https://pedrovfigueiredo.github.io/projects/manylights/SIGGRAPH_2025_Importance_Sampling/index.html"
# Content
abstract: |
    We propose a neural approach for estimating spatially varying light selection distributions to improve importance sampling in Monte Carlo rendering, particularly for complex scenes with many light sources. Our method uses a neural network to predict the light selection distribution at each shading point based on local information, trained by minimizing the KL-divergence between the learned and target distributions in an online manner. To efficiently manage hundreds or thousands of lights, we integrate our neural approach with light hierarchy techniques, where the network predicts cluster-level distributions and existing methods sample lights within clusters. Additionally, we introduce a residual learning strategy that leverages initial distributions from existing techniques, accelerating convergence during training. Our method achieves superior performance across diverse and challenging scenes.

teaser_caption: |
  XXX
# Optional: Video embed (YouTube, Vimeo, etc.)
# video_embed: "https://www.youtube.com/embed/your-video-id"

# bibtex: |
#   @inproceedings{figueiredo2025neural,
#     title={Neural Importance Sampling of Many Lights},
#     author={Figueiredo, Pedro and He, Qihao and Bako, Steve and Kalantari, Nima Khademi},
#     booktitle={ACM SIGGRAPH 2025},
#     year={2025}
#   }

thumbnail: "thumbnail.jpg" # Path relative to _index.md
---