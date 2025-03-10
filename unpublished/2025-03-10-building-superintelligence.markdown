---
layout: post
title:  "How to Build Superintelligence"
date:   2025-03-10 14:00:37 +0200
categories: posts
---

**I believe we have figured out most of the building blocks required to build superintelligent AI**. There are more details left to work out, but the picture is becoming clearer.
{: .text-justify}


The goal of this post is to bring you up-to-speed, even if you haven't been following AI research closely for the past 2 years, and don't have a background in AI.
{: .text-justify}

We will focus on recent advancements in reasoning models, specifically DeepSeek R1, and how it opens up possibilities for rapid advancement in capabilities, utilizing existing research and methods. 
{: .text-justify}

Before we begin, I want to thank *acknowledgements* for help with this post.

## Two Stages of Training

LLM training can generally be divided into two stages.

<p align="center">
    <img src="/pictures/building-superintelligence/pre-training.png">
</p>

* **Pre-training** is the process of training the model on the entire internet. This part is very expensive, with some AI labs purchasing upwards of $3 Billion of hardware for it. The resulting model is usually called a **Base Model**.
* **Post-training** consists of various methods used to adapt the base model so that it can be used as a product, like ChatGPT.

The jump from GPT-3 to ChatGPT was the introduction of the post-training stage. Earlier models like GPT-2 consisted entirely of what we now call pre-training.

Up until recently, the post-training stage of most LLMs consisted of two parts.

<p align="center">
    <img src="/pictures/building-superintelligence/chatgpt-pipeline.png">
</p>

Reasoning models are enabled by the introduction of another post-training method.

<p align="center">
    <img src="/pictures/building-superintelligence/reasoning-models.png">
</p>

## Two Methods of Training

Learning algorithms can generally be divided into two classes:

* **Supervised Learning** algorithms teach a model using pre-collected data. In the case of LLMs, the model is trained to predict the next word in a text from the dataset. The end result is that the model learns to *mimic* the dataset well.
* **Reinforcement Learning** algorithms let the model generate a full text. Then, the text is ranked according to some 

