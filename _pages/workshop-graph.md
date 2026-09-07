---
permalink: /workshop-graph/
title: "Workshop on Graph Algorithms"
author_profile: false
redirect_from: 
---

We are happy to host a workshop on graph algorithms at [TU Wien](https://tuwien.at).

**Date and time:** September 9, 2026, 9:00-17:00

**Location:** Karlsplatz 13, 1040 Wien, in Lecture Hall 14A (Günther
		Feuerstein). See [Google Maps](https://maps.app.goo.gl/bU5QjzteGTUZZjXd8)
		for instructions how to get there and
		[here](../files/getting-to-lecture-hall-14a.pdf) for instructions how
		to find the room.

**Program committee:** Sebastian Forster (Uni Salzburg),
	Gramoz Goranci (Uni Wien), Stefan Neumann (TU Wien)

**Local organizer:** Stefan Neumann (TU Wien)

Attendance is free but please register by sending a mail to Stefan Neumann.
If you have any questions, please also send a mail to Stefan Neumann.

The workshop has received sponsoring from [ISTA](https://ista.ac.at).

<img src="../files/TUW.png" alt="TU Wien Logo" height="80">
<img src="../files/ISTA.jpg" alt="ISTA Logo" height="80">


## Program

| Time          | Speaker                             | Talk                                                                                                                                            |
| ------------- | ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| 9:00 – 9:05   | Organizers                          | Welcome                                                                                                                                         |
| 9:05 – 9:35     | Sayan Bhattacharya (Warwick)        | [Recent Advances in Dynamic Matching](#recent-advances-in-dynamic-matching)                                                                                                             |
| 9:35 – 10:05    | Danupon Nanongkai (MPI Informatics) | TBD                                                                                                                                             |
| 10:05 – 10:20   | Kathrin Hanauer (Uni Wien)          | Fully Dynamic Triangle and 4-Vertex Subgraph Counting: From Theory to Practice and Back Again                                                   |
| 10:20 – 10:50 |                                     | **Coffee Break**                                                                                                                                |
| 10:50 – 11:20   | Robert Tarjan (Princeton)           | [Musings on Medians](#musings-on-median)                                                                                                                              |
| 11:20 – 11:50   | Harald Räcke (TU München)           | [An Improved Quality Hierarchical Congestion Approximator in Near-Linear Time](#an-improved-quality-hierarchical-congestion-approximator-in-near-linear-time)                                                                    |
| 12:00 – 13:00 |                                     | **Lunch**                                                                                                                                       |
| 13:15 – 13:45   | David Williamson (Cornell)          | [The 4/3 Conjecture for the Traveling Salesman Problem: A Status Update](#the-43-conjecture-for-the-traveling-salesman-problem-a-status-update)                                                                          |
| 13:45 – 14:00   | Christian Schulz (Uni Heidelberg)   | [Agentic Algorithm Engineering: Improving Shared-Memory Exact Minimum Cuts](#agentic-algorithm-engineering-improving-shared-memory-exact-minimum-cuts)                                                                       |
| 14:00 – 14:45   |                                     | Open forum                                                                                                                                      |
| 14:45 – 15:15 |                                     | **Coffee Break**                                                                                                                                |
| 15:15 – 15:45   | Jalaj Upadhyay (Rutgers)            | [Chasing the constant and its implications in private learning](#chasing-the-constant-and-its-implications-in-private-learning) |
| 15:45 – 16:15   | Pan Peng (USTC)                     | [Spectral Amplification for Private Graph Release](#spectral-amplification-for-private-graph-release)                                                                                                |
| 16:15 – 16:30   | Paul Duetting (Google)              | The AdWords Problem                                                                                                                             |
| 16:30 – 16:45   | Claire Mathieu (CNRS and Brown)     |                                                                                                                                                |
| 16:45 – 17:00   | Organizers                          | Closing Remarks                                                                                                                                 |

Below you can find more detailed information about some of the talks.

## Abstracts

### Recent Advances in Dynamic Matching {#recent-advances-in-dynamic-matching}

**Speaker:** Sayan Bhattacharya, Warwick

**Abstract:**
Consider a graph $G = (V, E)$ that is undergoing a sequence of edge insertions/deletions. We want to design an algorithm that maintains a large matching in this dynamic graph G with small "update time". Here, the "update time" of an algorithm refers to the time it takes to handle the insertion/deletion of an edge in $G$. Ideally, we would like to ensure that the update time of our algorithm is polylogarithmic in the number of nodes in $G$. This problem has received considerable attention within the dynamic algorithms community in the past decade. In this talk, I will present an overview of some very recent developments on this problem, which point to surprising connections between dynamic and sublinear algorithms.

---

### Musings on Median {#musings-on-median}

**Speaker:** Robert Tarjan, Princeton

**Abstract:**
It has been known since 1972 that the median of a set of numbers can be found in worst-case linear time and comparisons by using a doubly recursive "median of medians" algorithm. The original algorithm computes medians of subsets of size five. A natural question is whether  subsets of size three suffice. We shall show that this is indeed the case, if we slightly generalize the algorithm in a natural way.

---

### An Improved Quality Hierarchical Congestion Approximator in Near-Linear Time {#an-improved-quality-hierarchical-congestion-approximator-in-near-linear-time}

**Speaker:** Harald Räcke, TU München

**Abstract:**
A single-commodity congestion approximator for a graph is a compact data structure that approximately predicts the edge congestion required to route any set of single-commodity flow demands in a network. A hierarchical congestion approximator (HCA) consists of a laminar family of cuts in the graph and has numerous applications in approximating cut and flow problems in graphs, designing efficient routing schemes, and managing distributed networks.  
  
There is a tradeoff between the running time for computing an HCA and its  approximation quality. The best polynomial-time construction in an $n$-node graph gives an HCA with approximation quality $O(\log^{1.5}n \log \log n)$. Among near-linear time algorithms, the best previous result achieves approximation quality $O(\log^4 n)$. We improve upon the latter result by giving the first near-linear time algorithm for computing an HCA with approximation quality $O(\log^2 n \log \log n)$.  
  
Additionally, our algorithm can be implemented in the parallel setting with polylogarithmic span and near-linear work, achieving the same approximation quality. This improves upon the best previous such algorithm, which has an $O(\log^9n)$ approximation quality. We also present a lower bound of $\Omega(\log n)$ for the approximation guarantee of hierarchical congestion approximators.  
  
This is joint work with Monika Henzinger, and Robin Münk.

---

### The 4/3 Conjecture for the Traveling Salesman Problem: A Status Update {#the-43-conjecture-for-the-traveling-salesman-problem-a-status-update}

**Speaker:** David Williamson, Cornell

**Abstract:**
The 4/3 conjecture for the traveling salesman problem (TSP) states that the standard linear programming relaxation for the TSP has an integrality gap of 4/3 in the case of the symmetric TSP instances that obey the triangle inequality.  In this talk, I will survey what we know about the status of this conjecture and special cases for which we know that the conjecture is true.

---

### Agentic Algorithm Engineering: Improving Shared-Memory Exact Minimum Cuts {#agentic-algorithm-engineering-improving-shared-memory-exact-minimum-cuts}

**Speaker:** Christian Schulz, Uni Heidelberg

**Abstract:**
The minimum cut problem asks us to divide the nodes of an undirected edge-weighted graph into two blocks while minimizing the weighted sum of the cut edges. Our fastest exact algorithm, available in the open-source package VieCut, outperformed the previously fastest solvers by a factor of up to 2.5 sequentially and up to 12.9 in parallel. In this talk, we improve it using agentic algorithm engineering, a methodology in which autonomous LLM agents run the algorithm engineering cycle on an existing code base: they form hypotheses about where running time is lost, implement them, benchmark the result and keep or discard the change. Even though the algorithm was already extensively hand-tuned, the agent finds significant further optimizations, in particular on worst-case instances.

---

### Chasing the constant and its implications in private learning {#chasing-the-constant-and-its-implications-in-private-learning}

**Speaker:** Jalaj Upadhyay, Rutgers

**Abstract:**
In this talk, we will discuss recent works that establish deep connections between private continual counting and a concept in matrix analysis (factorization norms) with its applications in private training. We then discuss the series of recent results that improve upon more than three decades-old results in matrix analysis. In particular, we will show an upper and lower bound on its norm with an additive gap of $0.14 + o(1)$. Moreover, the upper bound is achieved by an explicit factorization.

---

### Spectral Amplification for Private Graph Release {#spectral-amplification-for-private-graph-release}

**Speaker:** Pan Peng, USTC

**Abstract:**
How can we release useful information about a large network while protecting the privacy of each individual connection? We study this question under edge-level differential privacy, with the goal of constructing a synthetic graph that approximately preserves the size of every cut in the original graph. If only additive error is permitted, an error of roughly $n^{3/2}$ is unavoidable in the worst case. Allowing a small multiplicative slack makes substantially better accuracy possible, but previously known efficient algorithms still incurred additive error roughly $n^{5/4}$. We give a polynomial-time algorithm that improves this error to $n^{13/12+o(1)}$.

Our main idea is spectral amplification: we transform the graph’s spectrum so that its important structural information can be distinguished more effectively from the noise required for privacy. We then combine this idea with a recursive graph-decomposition framework to obtain the improved guarantee.
