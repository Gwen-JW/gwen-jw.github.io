---
# layout: post
title: "XAI research summary and trends"
date: 2025-02-04
tags: ["XAI", "review"]
author: ["Jiawen Wei"]
---

## Methodologies

### 1. Attribution methods
Some methods contribute to the explanation of Deep Learning (DL) models by computing the importance/relevance of input features, like Local Interpretable Model-ggnostic Explanations (LIME), Shapley Additive Explanation (SHAP), etc. Some methods utilize network gradients, like saliency maos, Deconvolutional Neural Networks (DeConvNet), Layer-Wise Relevance Propagation (LRP), Pattern Attribution, and Randomized Input Sampling for Explanation (RISE), etc.

### 2. Ante-hoc explainable models
Traditional Machine Learning (ML) methods are often adopted for ante-hoc methods, especially techniques based on Decision Trees (DTs). Anothor recent development in XAI is rule-based approaches.

### 3. New kind of methods
Recently, some methods integrate attention mechanism into the nerual network architectures to provide explanations. 


## Oppoturnities and Challenges

### 1. explanations of new AI architectures
**Mechanistic interpretability** can be an option to gain deep insights into generative models, like Variational Autoencoders (VAEs), Generative Adversarial Networks (GANs), Large Language Models (LLMs), etc.

### 2. improving XAI methods
Attribution methods have limitations. For example, attribution-based explanations are vulnerable to input perturbations, parameter custimization (selction of baselines), etc. One solution can be aggregating explanations of different XAI methods to gain a more accurate and robust explanation.

### 3. Concept-based methods
Concept-based learning methods are a popular class of approaches which could be used for both post-hoc and ante-hoc explanations. Many recent algorithms describe "prototypical concepts" or "prototypes", like ProtoPNet, ProtoTree, ProtoPShare, Concept Bottleneck Models, concept Activation Vectors, Concept Embedding Models, Concept Atlases, etc. Neuro-symbolic learning and knowledge graphs are also popular methods fall within concept-based approaches.