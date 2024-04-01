---
title: "HawkEye: Training Video-Text LLMs for Grounding Text in Videos"
authors: "<b>Yueqian Wang</b>, Xiaojun Meng, Jianxin Liang, Yuxuan Wang, Qun Liu, Dongyan Zhao"
collection: publications
permalink: /publication/2024-arxiv-hawkeye
excerpt: 'One of the first video-text LLMs that can perform temporal video grounding in a fully text-to-text manner, and InternVid-G, a large-scale video-text dataset for video grounding training.'
date: 2024-03-15
venue: 'arXiv:2403.10228'
paperurl: 'https://arxiv.org/abs/2403.10228'
---

Abstract: Video-text Large Language Models (video-text LLMs) have shown remarkable performance in answering questions and holding conversations on simple videos. However, they perform almost the same as random on grounding text queries in long and complicated videos, having little ability to understand and reason about temporal information, which is the most fundamental difference between videos and images. In this paper, we propose HawkEye, one of the first video-text LLMs that can perform temporal video grounding in a fully text-to-text manner. To collect training data that is applicable for temporal video grounding, we construct InternVid-G, a large-scale video-text corpus with segment-level captions and negative spans, with which we introduce two new time-aware training objectives to video-text LLMs. We also propose a coarse-grained method of representing segments in videos, which is more robust and easier for LLMs to learn and follow than other alternatives. Extensive experiments show that HawkEye is better at temporal video grounding and comparable on other video-text tasks with existing video-text LLMs, which verifies its superior video-text multi-modal understanding abilities. Code: https://github.com/yellow-binary-tree/HawkEye
