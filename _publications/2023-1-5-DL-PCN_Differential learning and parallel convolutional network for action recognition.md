---
title: "DL-PCN: Differential learning and parallel convolutional network for action recognition"
collection: publications
permalink: /publication/2023-1-5-DL-PCN_Differential learning and parallel convolutional network for action recognition
excerpt: 'This paper introduces a lightweight network, a Differential Learning and Parallel Convolutional Networks (DL-PCN), to reduce the computational burden of GCN skeleton action recognition method.'
date: 2023-1-5
venue: 'AI COMMUNICATION'
paperurl: 'https://content.iospress.com/articles/ai-communications/aic220268'
citation: 'Zeng, Qinyang, et al. "DL-PCN: Differential learning and parallel convolutional network for action recognition." AI Communications Preprint (2023): 1-15.'
---
Abstract: Graph Convolution Network (GCN) algorithms have greatly improved the accuracy of skeleton-based human action recognition. GCN can utilize the spatial information between skeletal joints in subsequent frames better than other deep learning algorithms, which is beneficial for achieving high accuracy. However, the traditional GCN algorithms consume lots of computation for the stack of multiple primary GCN layers. Aiming at solving the problem, we introduce a lightweight network, a Differential Learning and Parallel Convolutional Networks (DL-PCN), whose key modules are Differential Learning (DLM) and the Parallel Convolutional Network (PCN). DLM features a feedforward connection, which carries the error information of GCN modules with the same structure, where GCN and CNN modules directly extract the original information from the input data, making the spatiotemporal information extracted by these modules more complete than that of GCN and CNN tandem structure. PCN comprises GCN and Convolution Neural Network (CNN) in parallel. Our network achieves comparable performance on the NTU RGB+D 60 dataset, the NTU RGB+D 120 dataset and the Northwestern-UCLA dataset while considering both accuracy and calculation parameters.

[Download paper here](https://content.iospress.com/articles/ai-communications/aic220268)