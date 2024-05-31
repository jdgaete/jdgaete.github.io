---
layout: page
title: Frequency Based Histogram Query Optimizer 
description: Frequency Based Histogram Query Optimizer 
img: assets/img/freq.jpg
importance: 3
category: work
---

The selection of join order is a crucial task in the query optimizer of a DBMS. It involves identifying the optimal join order with the minimum possible cost among all possible options, which is an NP-hard problem due to the exponentially growing search space (Chen et al., 2023). As a result, it has been a persistent challenge in query optimization, especially for queries with a large number of joins. In this study, we propose a fast and effective approach to determine good join orders. Our deterministic dynamic programming algorithm is combined by a frequency based histogram to estimate join size parameters. We evaluate our approach using Join Order Benchmark (JOB) (Leis et al., 2018) and compare it to PostgreSQL plan estimates and natural join parameter assumptions.

[CODE](https://gitlab.com/xxks-kkk/histogram-optimizer/-/tree/master?ref_type=heads)
[REPORT](https://drive.google.com/file/d/1TFXjs4QxcK_qZJAbbTJm-rGloZd7wkYc/view?usp=sharing)