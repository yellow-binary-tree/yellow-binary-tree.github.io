---
title: "LSTP: Language-guided Spatial-Temporal Prompt Learning for Long-form Video-Text Understanding"
authors: "Yuxuan Wang, <b>Yueqian Wang</b>, Pengfei Wu, Jianxin Liang, Dongyan Zhao, Zilong Zheng"
collection: publications
permalink: /publication/2024-arxiv-lstp
excerpt: "Intergrating optical flow for relevant content selection to improve video-text LLMs' abilities on videoqa."
date: 2024-01-01
venue: "arXiv:2402.16050"
paperurl: "https://arxiv.org/abs/2402.16050"
---

Abstract: Despite progress in video-language modeling, the computational challenge of interpreting long-form videos in response to task-specific linguistic queries persists, largely due to the complexity of high-dimensional video data and the misalignment between language and visual cues over space and time. To tackle this issue, we introduce a novel approach called Language-guided Spatial-Temporal Prompt Learning (LSTP). This approach features two key components: a Temporal Prompt Sampler (TPS) with optical flow prior that leverages temporal information to efficiently extract relevant video content, and a Spatial Prompt Solver (SPS) that adeptly captures the intricate spatial relationships between visual and textual elements. By harmonizing TPS and SPS with a cohesive training strategy, our framework significantly enhances computational efficiency, temporal understanding, and spatial-temporal alignment. Empirical evaluations across two challenging tasks--video question answering and temporal question grounding in videos--using a variety of video-language pretrainings (VLPs) and large language models (LLMs) demonstrate the superior performance, speed, and versatility of our proposed LSTP paradigm.