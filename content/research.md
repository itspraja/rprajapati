---
title: Research
description: Projects and Research Focus
showPagination: false
showDate: false
showAuthor: false
showReadingTime: false
showTableOfContents: true
---

My work sits at the intersection of **streaming graph algorithms**, 
**distributed systems**, and **GPU-accelerated computing**. 
The unifying theme: using graphs as a first-principles framework 
to make large-scale computation fast, correct, and practical.

---

## SAGA — State-Aware Streaming Graph Analytics

Large graphs change continuously — edges are inserted and deleted 
at high throughput. Most systems recompute analytics from scratch 
on each update, which doesn't scale. SAGA is a distributed framework 
that maintains analytical state incrementally over dynamic graphs, 
propagating only the changes that matter across partitions.

*Accepted · HPDC 2026*

---

## StreamGC — Real-Time Vertex Coloring on Parallel Systems

Vertex coloring assigns labels to nodes such that no two adjacent 
nodes share a label. In the streaming setting, edges arrive in 
batches and the coloring must be maintained without global 
synchronization. StreamGC handles this on parallel systems 
with low update latency.

---

## Past Work

**Semantic PageRank** *(M.Tech Thesis, IIT Jodhpur · 2022–2024)*  
Extended classical PageRank with knowledge graph signals to improve 
ranking quality on academic corpora. Applied distributed graph 
processing on Apache Spark GraphX.
