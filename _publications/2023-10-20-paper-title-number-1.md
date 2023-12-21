---
title: "Prediction of multi-relational drug–gene interaction via Dynamic hyperGraph Contrastive Learning"
collection: publications
permalink: /publication/2023-10-20-paper-title-number-1
excerpt: 'We present a general dynamic hypergraph contrastive learning framework for multi-relational DGI prediction, with remarkable effectiveness, robustness and generalization.'
date: 2023-10-20
venue: 'Briefings in Bioinformatics'
paperurl: 'http://wentao228.github.io/files/DGCL.pdf'

---
[Download paper here](http://wentao228.github.io/files/DGCL.pdf)


## Abstract

Drug–gene interaction prediction occupies a crucial position in various areas of drug discovery, such as drug repurposing, lead discovery and off-target detection. Previous studies show good performance, but they are limited to exploring the binding interactions and ignoring the other interaction relationships. Graph neural networks have emerged as promising approaches owing to their powerful capability of modeling correlations under drug–gene bipartite graphs. Despite the widespread adoption of graph neural network-based methods, many of them experience performance degradation in situations where high-quality and sufficient training data are unavailable. Unfortunately, in practical drug discovery scenarios, interaction data are often sparse and noisy, which may lead to unsatisfactory results. To undertake the above challenges, we propose a novel Dynamic hyperGraph Contrastive Learning (DGCL) framework that exploits local and global relationships between drugs and genes. Specifically, graph convolutions are adopted to extract explicit local relations among drugs and genes. Meanwhile, the cooperation of dynamic hypergraph structure learning and hypergraph message passing enables the model to aggregate information in a global region. With flexible global-level messages, a self-augmented contrastive learning component is designed to constrain hypergraph structure learning and enhance the discrimination of drug/gene representations. Experiments conducted on three datasets show that DGCL is superior to eight state-of-the-art methods and notably gains a 7.6% performance improvement on the DGIdb dataset. Further analyses verify the robustness of DGCL for alleviating data sparsity and over-smoothing issues.