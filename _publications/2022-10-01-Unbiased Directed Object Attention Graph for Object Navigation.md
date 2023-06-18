---
title: "Unbiased Directed Object Attention Graph for Object Navigation"
collection: publications
permalink: /publication/2022-10-01-Unbiased Directed Object Attention Graph for Object Navigation
excerpt: 'This paper discovers the problem of object attention bias in visual object navigation tasks and solves it using directed object attention (DOA) graph.'
date: 2022-10-1
venue: 'ACMMM'
paperurl: 'http://academicpages.github.io/files/Unbias_directed_object_attention_graph_for_object_navigation.pdf'
citation: 'Dang, Ronghao, et al. "Unbiased Directed Object Attention Graph for Object Navigation." Proceedings of the 30th ACM International Conference on Multimedia. 2022.'
---
Abstract: Object navigation tasks require agents to locate specific objects in unknown environments based on visual information. Previously, graph convolutions were used to implicitly explore the relationships between objects. However, due to differences in visibility among objects, it is easy to generate biases in object attention. Thus, in this paper, we propose a directed object attention (DOA) graph to guide the agent in explicitly learning the attention relationships between objects, thereby reducing the object attention bias. In particular, we use the DOA graph to perform unbiased adaptive object attention (UAOA) on the object features and unbiased adaptive image attention (UAIA) on the raw images, respectively. To distinguish features in different branches, a concise adaptive branch energy distribution (ABED) method is proposed. We assess our methods on the AI2-Thor dataset. Compared with the state-of-the-art (SOTA) method, our method reports 7.4%, 8.1% and 17.6% increase in success rate (SR), success weighted by path length (SPL) and success weighted by action efficiency (SAE), respectively.

[Download paper here](http://academicpages.github.io/files/Unbias_directed_object_attention_graph_for_object_navigation.pdf)