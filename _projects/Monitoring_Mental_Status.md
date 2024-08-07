---
layout: page
title: Monitoring Mental Health Status
description: Using Social Media Data 
img: /assets/img/projects_preview/p1_img.jpg
importance: 1
related_publications: true
---

## Research Background
The global healthcare system faces significant challenges from mental health conditions such as depression and suicidal ideation, emphasizing the need for an advanced monitoring system for early intervention.

Social media platforms provide an easily accessible and time-saving communication approach for individuals with mental disorders compared to face-to-face meetings with medical providers. Recently, machine learning (ML)-based mental health exploration using large-scale social media data has attracted significant attention {% cite kim2021machine %}.

<img src="/assets/img/projects_preview/p1_socialmedia.png" width="80%" title="p1_socialmedia"/>

## Research Goal
We aims to help to establish a prevention system for early detection and immediate intervention of individuals with high-risk mental status for clinical support using social media data. This will enable us to reduce mental health-related social costs and promote public health.

<img src="/assets/img/projects_preview/p1_frame.png" width="80%" title="p1_frame"/>


## Approach
- __Mood-Aware Multi-Task Learning for Detecting Bipolar Disorder from Misdiagnosed Major Depressive Disorder__ {% cite lee2024detecting %}: 

    This study presents a novel approach for identifying BD risk in individuals initially misdiagnosed with MDD. A unique dataset, BD-Risk, is introduced, incorporating mental disorder types and BD mood levels verified by two clinical experts. The proposed multi-task learning for predicting BD risk and BD mood level outperforms the state-of-the-art baselines.

- __Using Large Language Model for Explainable Suicidality Prediction__ {% cite jeon2024dual %}: 

    In order to enhance interpretability of the suicidality prediction models, we propose a dual-prompting approach: (i) Knowledge-aware evidence extraction by leveraging the expert identity and a suicide dictionary with a mental health-specific LLM; and (ii) Evidence summarization by employing an LLM-based consistency evaluator. Comprehensive experiments demonstrate the effectiveness of combining domain-specific information.

- __Temporal Bipolar symptom-aware attention mechanism__ {% cite lee2023towards %}:

  We build a novel BD dataset clinically validated by psychiatrists, including 14 years of posts on bipolar-related subreddits written by 818 BD patients, along with the annotations of future suicidality and BD symptoms. We also suggest a temporal symptom-aware attention mechanism to determine which symptoms are the most influential for predicting future suicidality over time through a sequence of BD posts.

- __Graph Neural Network with Domain Knowledge for Capturing Suicide-related Context__ {% cite lee2022detecting %}: 

    Using a suicide dictionary created by mental health experts is one of the effective ways to detect suicidal ideation. We apply GNNs to grasp how the word can be associated with the suicide-related context by learning the relations between a given post and words.
      
- __Cross-lingual Suicide Risk Detection for Low-Resource Language__ {% cite lee2020cross %}:

    To utilize the existing suicide dictionaries developed for other languages (i.e., English and Chinese) in word embedding, our model translates a post written in the target language (i.e., Korean) into English and Chinese, and then uses the separate suicidal-oriented word embeddings developed for English and Chinese, respectively. By applying an ensemble approach for different languages, the model achieves high accuracy.


