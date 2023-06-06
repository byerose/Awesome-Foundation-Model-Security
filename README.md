[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/byerose/Awesome-Generative-AI-Security) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
> 🚩 Recently, there have been significant advances in generative models, including the diffusion model in the field of image processing, large language models in the field of text processing, and even diffusion models that have been extended to speech and video processing. The rapid development of generative models has forced us to consider their security issues. This repository primarily focuses on the security issues arising from generative models and how to use generative models to address the problems of adversarial machine learning.

# Table of Contents
- [Survey](#Survey)
- [Awesome](#Awesome)
- [Representative Model](#Representative-Model)
- [Risks of Model](#Risks-of-Model)
  - [Evasion Attacks](#Evasion-Attacks)
  - [Prompt Injection](#Prompt-Injection)
  - [Poisoning](#Poisoning)
  - [Privacy](#Privacy)
- [Evaluation](#Evaluation)
- [Improving](#Improving)
- [Face to Security](#Face-to-Security)
  - [Attack](#Attack)  
  - [Adversarial Robustness](#Adversarial-Robustness)
- [Workshop&Talks](#Workshop&Talks)

# Survey

- Diffusion Models in NLP: A Survey [[ArXiv '23]](https://arxiv.org/abs/2303.07576) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- A Survey of Large Language Models [[ArXiv '23]](http://arxiv.org/abs/2303.18223) [[code]](https://github.com/RUCAIBox/LLMSurvey) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Diffusion Models: A Comprehensive Survey of Methods and Applications [[ArXiv '22]](https://arxiv.org/abs/2209.00796) [[code]](https://github.com/YangLing0818/Diffusion-Models-Papers-Survey-Taxonomy) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- Shortcut Learning of Large Language Models in Natural Language Understanding: A Survey [[ArXiv '22]](https://arxiv.org/abs/2208.11857) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- A Survey of Evaluation Metrics Used for NLG Systems [[CUSR '22]](https://dl.acm.org/doi/abs/10.1145/3485766) <img src="https://img.shields.io/badge/nlp-informational" alt="" />

# Awesome

- A collection of papers and resources related to Large Language Models [[code]](https://github.com/RUCAIBox/LLMSurvey) <img src="https://img.shields.io/badge/multi-blueviolet" alt="" />
- Awesome-LLM: a curated list of Large Language Model [[code]](https://github.com/Hannibal046/Awesome-LLM) <img src="https://img.shields.io/badge/multi-blueviolet" alt="" />
- Tracking Papers on Diffusion Models [[code]](https://vsehwag.github.io/blog/2023/2/all_papers_on_diffusion.html) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- Awesome-LLM-Uncertainty-Reliability-Robustness [[code]](https://github.com/jxzhangjhu/Awesome-LLM-Uncertainty-Reliability-Robustness) <img src="https://img.shields.io/badge/nlp-informational" alt="" />

# Representative Model

- Improved Denoising Diffusion Probabilistic Models [[ICML '21]](https://arxiv.org/abs/2102.09672) [[code]](https://github.com/openai/improved-diffusion) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- CodeGen: An Open Large Language Model for Code with Multi-Turn Program Synthesis [[ICLR '23]](https://arxiv.org/abs/2203.13474) [[code]](https://github.com/salesforce/CodeGen) <img src="https://img.shields.io/badge/nlp-informational" alt="" />

# Risks of Model

## Evasion Attacks

- Adversarial Demonstration Attacks on Large Language Models [[ArXiv '23]](https://arxiv.org/abs/2305.14950) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Adversarial Prompting for Black Box Foundation Models [[ArXiv '23]](https://arxiv.org/abs/2302.04237)  <img src="https://img.shields.io/badge/nlp-informational" alt="" />

## Prompt Injection

- More than you've asked for: A Comprehensive Analysis of Novel Prompt Injection Threats to Application-Integrated Large Language Models [[ArXiv '23]](https://arxiv.org/abs/2302.12173) [[code]](https://github.com/greshake/lm-safety) <img src="https://img.shields.io/badge/nlp-informational" alt="" />

## Poisoning

- Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models [[[ArXiv '23]](https://arxiv.org/abs/2305.14710) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- BadGPT: Exploring Security Vulnerabilities of ChatGPT via Backdoor Attacks to InstructGPT [[NDSS '23 Poster]](https://arxiv.org/abs/2304.12298) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Analyzing And Editing Inner Mechanisms of Backdoored Language Models [[ArXiv '23]](http://arxiv.org/abs/2302.12461) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Poisoning Language Models During Instruction Tuning [[ICML '23]](http://arxiv.org/abs/2305.00944) [[code]](https://github.com/AlexWan0/Poisoning-Instruction-Tuned-Models) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Text-to-Image Diffusion Models can be Easily Backdoored through Multimodal Data Poisoning [[ArXiv '23]](https://arxiv.org/abs/2305.04175) <img src="https://img.shields.io/badge/multi-blueviolet" alt="" />
- TrojDiff: Trojan Attacks on Diffusion Models with Diverse Targets [[CVPR '23]](https://arxiv.org/abs/2303.05762) [[code]](https://github.com/chenweixin107/TrojDiff) <img src="https://img.shields.io/badge/multi-blueviolet" alt="" />
  
## Privacy

- Prompt Stealing Attacks Against Text-to-Image Generation Models [[ArXiv '23]](https://arxiv.org/abs/2305.13873) <img src="https://img.shields.io/badge/multi-blueviolet" alt="" />
- Multi-step Jailbreaking Privacy Attacks on ChatGPT [[ArXiv '23]](http://arxiv.org/abs/2304.05197) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Extracting training data from diffusion models [[ArXiv '23]](https://arxiv.org/abs/2301.13188)  <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- Extracting Training Data from Large Language Models [[USENIX '21]](https://arxiv.org/abs/2012.07805) [[code]](https://github.com/ftramer/LM_Memorization) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Are Diffusion Models Vulnerable to Membership Inference Attacks? [[ArXiv '23]](https://arxiv.org/abs/2302.01316) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- On the Risks of Stealing the Decoding Algorithms of Language Models [[ArXiv '23]](https://arxiv.org/abs/2303.04729)  <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Sentence Embedding Leaks More Information than You Expect: Generative Embedding Inversion Attack to Recover the Whole Sentence [[ACL '23]](https://arxiv.org/abs/2305.03010) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
  
# Evaluation

- SneakyPrompt: Evaluating Robustness of Text-to-image Generative Models' Safety Filters [[ArXiv '23]](https://arxiv.org/abs/2305.12082) <img src="https://img.shields.io/badge/multi-blueviolet" alt="" />
- Model evaluation for extreme risks [[ArXiv '23]](https://arxiv.org/abs/2305.15324) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- LEVER: Learning to Verify Language-to-Code Generation with Execution [[ArXiv]](https://arxiv.org/abs/2302.08468) [[code]](https://github.com/niansong1996/lever) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Holistic Evaluation of Language Models [[ArXiv '22]](https://arxiv.org/abs/2211.09110) [[code]](https://github.com/stanford-crfm/helm) [[project]](https://crfm.stanford.edu/helm/latest/) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- How Secure is Code Generated by ChatGPT? [[ArXiv '22]](https://arxiv.org/abs/2304.09655) [[code]](https://github.com/raphaelkhoury/programsgeneratedbychatgpt) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- On the Robustness of ChatGPT: An Adversarial and Out-of-distribution Perspective [[ICLR '23 workshop]](http://arxiv.org/abs/2302.12095) [[code]](https://github.com/microsoft/robustlearn/tree/main/chatgpt-robust) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- How Robust is GPT-3.5 to Predecessors? A Comprehensive Study on Language Understanding Tasks [[ArXiv '23]](https://arxiv.org/abs/2303.00293) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- LEVER: Learning to Verify Language-to-Code Generation with Execution [[ArXiv '23]](http://arxiv.org/abs/2302.08468) [[code]](https://github.com/niansong1996/lever) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Is Your Code Generated by ChatGPT Really Correct? Rigorous Evaluation of Large Language Models for Code Generation [[ArXiv '23]](http://arxiv.org/abs/2305.01210) [[code]](https://github.com/evalplus/evalplus) <img src="https://img.shields.io/badge/nlp-informational" alt="" />

# Improving

- Prompting GPT-3 To Be Reliable [[ICLR '23]](https://arxiv.org/abs/2210.09150) [[code]](https://github.com/NoviScl/GPT3-Reliability) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Privacy-Preserving Prompt Tuning for Large Language Model Services [[ArXiv '23]](https://arxiv.org/abs/2305.06212) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
- Differentially Private Diffusion Models Generate Useful Synthetic Images [[ArXiv '23]](https://arxiv.org/abs/2302.13861) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- DE-FAKE: Detection and Attribution of Fake Images Generated by Text-to-Image Generation Models [[CCS '23]](https://arxiv.org/abs/2305.13873) <img src="https://img.shields.io/badge/multi-blueviolet" alt="" />
  
# Face to Security
## Attack
  - Controlling Large Language Models to Generate Secure and Vulnerable Code [[ArXiv '23]](https://arxiv.org/abs/2302.05319) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
  - ChatGPT as an Attack Tool: Stealthy Textual Backdoor Attack via Blackbox Generative Model Trigger [[ArXiv '23]](http://arxiv.org/abs/2304.14475) <img src="https://img.shields.io/badge/nlp-informational" alt="" />
  - Diffusion Models for Imperceptible and Transferable Adversarial Attack [[ArXiv '23]](https://arxiv.org/abs/2305.08192) [[code]](https://github.com/WindVChen/DiffAttack) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
  - Unsafe Diffusion: On the Generation of Unsafe Images and Hateful Memes From Text-To-Image Models [[CCS '23]](https://arxiv.org/abs/2305.13873) <img src="https://img.shields.io/badge/multi-blueviolet" alt="" />
  
## Adversarial Robustness 
- Improving Adversarial Robustness by Contrastive Guided Diffusion Process [[ArXiv '23]](https://arxiv.org/abs/2210.09643)
- DensePure: Understanding Diffusion Models towards Adversarial Robustness [[ICLR '23]](https://arxiv.org/abs/2211.00322) [[code]](https://github.com/Jayfeather1024/DensePure) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- DiffSmooth: Certifiably Robust Learning via Diffusion Models and Local Smoothing [[USENIX '23]](https://www.usenix.org/conference/usenixsecurity23/presentation/zhangjiawei) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- Defending against Adversarial Audio via Diffusion Model [[CVPR '23]](https://openreview.net/forum?id=5-Df3tljit7) [[code]](https://github.com/cychomatica/AudioPure) <img src="https://img.shields.io/badge/audio-important" alt="" />
- Diffusion Models for Adversarial Purification [[ICML '22]](https://arxiv.org/abs/2205.07460) [[code]](https://github.com/NVlabs/DiffPure) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- Better Diffusion Models Further Improve Adversarial Training [[ICML '23]](https://arxiv.org/abs/2302.04638) [[code]](https://github.com/wzekai99/dm-improves-at) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- Denoising Diffusion Probabilistic Models as a Defense against Adversarial Attacks [[ArXiv '22]](https://arxiv.org/abs/2301.06871) [[code]](https://github.com/ankile/adversarial-diffusion) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- Threat Model-Agnostic Adversarial Defense using Diffusion Models [[ArXiv '22]](https://arxiv.org/abs/2207.08089) [[code]](https://github.com/tsachiblau/Threat-Model-Agnostic-Adversarial-Defense-using-Diffusion-Models) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- Robust Learning Meets Generative Models: Can Proxy Distributions Improve Adversarial Robustness? [[ICLR '22]](https://arxiv.org/abs/2104.09425) [[code]](https://github.com/inspire-group/proxy-distributions) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />
- Adversarial Purification with Score-based Generative Models [[ICML '21]](http://proceedings.mlr.press/v139/yoon21a.html) [[code]](https://github.com/jmyoon1/adp) <img src="https://img.shields.io/badge/cv-brightgreen" alt="" />

# Workshop&Talks

- Challenges of Deploying Generative AI [[ICML '23]](https://deployinggenerativeai.github.io/index)
- Information-Theoretic Methods for Trustworthy Machine Learning [[Simons Institute '23]](https://simons.berkeley.edu/workshops/asu-it-ml)
