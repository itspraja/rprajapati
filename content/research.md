---
title: Research
description: Research focus and publications
showPagination: false
showDate: false
showAuthor: false
showReadingTime: false
showTableOfContents: true
---

My work sits at the intersection of **streaming graph algorithms**, **distributed systems**, and **GPU-accelerated computing** — using graphs as a unifying framework to make large-scale computation fast, correct, and practical.

---

## Focus Areas

**01 — Streaming Graph Systems**\
Algorithms and frameworks for real-time maintenance of large, evolving graphs — vertex coloring, maximal matching, and SimRank on continuous edge streams.

**02 — Distributed Graph Analytics**\
Scalable distributed frameworks for graph processing at scale, with attention to state management, fault tolerance, and partition-aware runtime efficiency.

**03 — Efficient LLM Deployment**\
Retrieval-augmented pipelines, model compression, and inference optimization on on-prem H100 GPU clusters for engineering workflows at Shell R&D.

**04 — Graph-Augmented AI**\
Using graph structure to improve representation learning, knowledge retrieval, and semantic ranking in large-scale information systems.

---

## Publications

`HPDC 2026` &nbsp; **SAGA: A Framework for State-Aware Streaming Graph Analytics**\
**Rohit Prajapati**, Dip Sankar Banerjee · Cleveland, OH, USA

Large graphs change continuously — edges arrive and depart at high throughput. SAGA maintains analytical state *incrementally* over dynamic graphs, propagating only the affected deltas across partitions rather than reprocessing the entire graph.

`SIGMOD 2026` &nbsp; **PJsim: Towards Precise and Scalable Graph Similarity**\
Prajjwal Nijhara, Jainan Tandel, **Rohit Prajapati**, Dip Sankar Banerjee · Bangalore, India

A precise, closed-form reformulation of SimRank that scales to large graphs without the approximation errors that plague existing methods.

`ICDCN 2026` &nbsp; **A Precise and Closed-Form Solution for Edge-Ranking**\
Prajjwal Nijhara, Jainan Tandel, **Rohit Prajapati**, Dip Sankar Banerjee · Nara, Japan

---

## In Progress

**StreamGC — Real-Time Vertex Coloring on Parallel Systems** *(in preparation)*\
Maintains graph colorings under continuous edge arrivals on parallel shared-memory systems, with low update latency and strong color-quality guarantees.
