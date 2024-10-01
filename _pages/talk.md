---
permalink: /talk/
title: "Mini-Workshop on Differential Privacy and Algorithms"
author_profile: false
redirect_from: 
---


On **October 16, 10:00-13:00**, we will host a mini-workshop on differential
privacy and algorithms. The talks will take place in **Karlsplatz 13, 1040 Wien, in
Seminarraum AE U1 - 7**.


## Talks

| Time            | Speaker                       | Title                                                             |
| ----------------        | ------                        | ------------------------------------------------------------ |
| 10:00-11:00     | Monika Henzinger (ISTA)       | Recent advances in differential privacy under continual observation |
| Break           |   | 
| 11:15-11:40     |  Bardiya Aryanfard (ISTA)     | Private and Simultaneous Estimation of Symmetric Norms under Continual Observation |
| 11:45-12:10     | A. R. Sricharan (Uni Wien)    | Incremental Approximate Maximum Flow from Residual Graph Sparsification |
| 12:15-12:40     | Sebastian Lüderssen (TU Wien) | Improved Four Cycle Counting in Low Degeneracy Graph Streams |


Below you can find more detailed information about some of the talks.


### Private and Simultaneous Estimation of Symmetric Norms under Continual Observation

**Speaker:** Bardiya Aryanfard, ISTA

**Abstract:** In this talk, I will present our recent result on estimating monotone symmetric norms in the continual observation model of differential privacy. In this setting, given a stream of items, upon each update the algorithm outputs an estimate of any monotone symmetric norm on the histogram of the items. Monotone symmetric norms (symmetric norms invariant to sign-flips and permutations) play a vital role in many applications of data analysis, e.g. detecting traffic anomalies and matrix optimization problems. However, ensuring privacy in such settings, particularly under continual observation remains a significant challenge. 
I will discuss an algorithm that provides differential privacy guarantees while simultaneously estimating all monotone symmetric norms on a frequency vector under continual observation. The talk will cover an introduction to the problem setting, the general ideas behind our algorithm, and an overview on the empirical evaluations.


### Incremental Approximate Maximum Flow from Residual Graph Sparsification

**Speaker**: A. R. Sricharan, Uni Wien

**Abstract:**
We will discuss an incremental algorithm for maintaining a $(1-\epsilon)$-approximate $s$-$t$ max flow in undirected, uncapacitated graphs in total time $\tilde{O}(m + nF^)$, where $m$ is the number of edge insertions and $F^$ is the final max flow value. The result is obtained by extending the residual graph sparsification technique of Karger and Levine [SIAM J. Comput. (2015)] to the incremental setting. Along the way, we will also extend the cut sparsification framework for undirected graphs of Fung et al. [SIAM J. Comput. (2019)] to balanced directed graphs.




### Improved Four Cycle Counting in Low Degeneracy Graph Streams

**Speaker:** Sebastian Lüderssen, TU Wien

**Abstract:** Given an undirected graph as a data stream of edges in arbitrary order, we consider the problem of estimating the number cycles of length 4 using sublinear space. We present a two-pass streaming algorithm, which returns a (1+epsilon)-approximation of the number of four cycles. A lower bound by McGregor and Vorotnikova (PODS'20) implies that our algorithm has an asymptotically optimal space complexity on bounded-degeneracy graphs.



