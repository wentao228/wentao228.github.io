---
title: "Learning to Denoise Unreliable Interactions for Link Prediction on Biomedical Knowledge Graph"
collection: publications
permalink: /publication/2023-12-09-paper-title-number-2
excerpt: 'We propose a Denoised Link Prediction framework to denoise unreliable interactions existing in the biomedical knowledge graph for link prediction.'
date: 2023-12-09
venue: 'arXiv'
paperurl: 'http://wentao228.github.io/files/DenoisedLP.pdf'

---
[Download paper here](http://wentao228.github.io/files/DenoisedLP.pdf)


## Abstract

Link prediction in biomedical knowledge graphs (KGs) aims at predicting unknown interactions between entities, including drug-target interaction (DTI) and drug-drug interaction (DDI), which is critical for drug discovery and therapeutics. Previous methods prefer to utilize the rich semantic relations and topological structure of the KG to predict missing links, yielding promising outcomes. However, all these works only focus on improving the predictive performance without considering the inevitable noise and unreliable interactions existing in the KGs, which limits the development of KG-based computational methods. To address these limitations, we propose a Denoised Link Prediction framework, called DenoisedLP. DenoisedLP obtains reliable interactions based on the local subgraph by denoising noisy links in a learnable way, providing a universal module for mining underlying task-relevant relations. To collaborate with the smoothed semantic information, DenoisedLP introduces the semantic subgraph by blurring conflict relations around the predicted link. By maximizing the mutual information between the reliable structure and smoothed semantic relations, DenoisedLP emphasizes the informative interactions for predicting relation-specific links. Experimental results on real-world datasets demonstrate that DenoisedLP outperforms state-of-the-art methods on DTI and DDI prediction tasks, and verify the effectiveness and robustness of denoising unreliable interactions on the contaminated KGs.