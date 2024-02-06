---
title: "Tree-based Focused Web Crawling with Reinforcement Learning"
collection: publications
date: 2021-12-12
venue: 'arXiv (to be submitted to IEEE TKDE)'
permalink: /publication/2021-12-12-paper-tres
---
---------------------------------------------------------------------------------------------------------------------------------------------------------------

### Recommended citation
**A. Kontogiannis**, D. Kelesis, V. Pollatos, G. Paliouras and G. Giannakopoulos. Tree-based Focused
Web Crawling with Reinforcement Learning . arXiv: 2112.07620 [cs.IR]. [doi](https://arxiv.org/abs/2112.07620)  

### Abstract  

A focused crawler aims at discovering as many web pages relevant to a target topic as possible, while avoiding irrelevant ones; i.e. maximizing the harvest rate. Reinforcement Learning (RL) has been utilized to optimize the crawling process, yet it deals with huge state and action spaces, which can constitute a serious challenge. In this paper, we propose TRES, an end-to-end RL-empowered framework for focused crawling. Unlike other approaches, we properly model a crawling environment as a Markov Decision Process, by representing the state as a subgraph of the Web and actions as its expansion edges. TRES adopts a keyword expansion strategy based on the cosine similarity of keyword embeddings. To learn a reward function, we propose a deep neural network, called KwBiLSTM, leveraging the discovered keywords. To reduce the time complexity of selecting a best action, we propose Tree-Frontier, a two-fold decision tree, which also speeds up training by discretizing the state and action spaces. Experimentally, we show that TRES outperforms state-of-the-art methods in terms of harvest rate by at least 58%, while it has competitive results in the domain maximization.
