---
title: "SMASH: Improving SMAll Language Models' Few-SHot Ability with Prompt-Based Distillation"
authors: "<b>Yueqian Wang</b>, Chang Liu, Kai Chen, Xi Wang, Dongyan Zhao"
collection: publications
permalink: /publication/2022-emnlp-smash
excerpt: 'Prompt-based learning and distillation for small transformer encoder-based language models.'
date: 2022-12-01
venue: 'Findings of the Association for Computational Linguistics: EMNLP'
paperurl: 'https://aclanthology.org/2022.findings-emnlp.492/'
---

Abstract: Large-scale language models coupled with prompts have shown remarkable performance on few-shot learning. However, through systematic experiments, we find that the few-shot performance of small language models is poor, and using prompts on them brings fewer improvements than on larger ones. In this paper, we propose SMASH, an approach to improve SMAll language models’ few-SHot ability by training on intermediate tasks before prompt-based fine-tuning on downstream tasks. We design intermediate tasks for sentence-pair tasks and sentiment classification tasks by creating training examples with prompt templates similar to downstream tasks using sentences sampled from a large-scale unsupervised corpus, and apply knowledge distillation to distill from outputs of larger pre-trained models as the training objective. We conduct extensive experiments and show that SMASH can make a 6-layer DistilRoBRETa-base achieve comparable performance on few-shot datasets with a 12-layer RoBERTa-base at a low cost.