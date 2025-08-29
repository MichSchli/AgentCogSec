<a href="url"><img src="Figures/example.png" align="center" height="30%" width="30%" ></a>

# Defenses Against Attacks by Content
List of papers on cognitive security for AI agents.

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)]([https://github.com/Cartus/Automated-Fact-Checking-Literature](https://github.com/MichSchli/AgentCogSec))
[![Last Commit](https://img.shields.io/github/last-commit/MichSchli/AgentCogSec)](https://github.com/MichSchli/AgentCogSec)
[![Contribution_welcome](https://img.shields.io/badge/Contributions-welcome-blue)](https://github.com/MichSchli/AgentCogSec/blob/main/contribute.md)

## Overview
This repo contains relevant resources from []. In this paper, we introduce attacks by content, a type of prompt injection where an attacker manipulates a RAG system or an AI agent by supplying biased, misleading, or false information. This differs from traditional prompt injection in that the surface form of the message is indistinguishable from legitimate content. The agent must therefore analyse the *content* of the message to identify the attack -- i.e., the agent must fact-check. In this repository, we curate a list of papers focusing on defending against such attacks. As the field evolves, we will provide timely updates in this repository.

- [Task Definition](#task-definition)
- [Claim Prioritisation](#claim-prioritisation)


## Task Definition

Text

In our paper, we propose a pipeline for defending against attacks by content:

<a href="url"><img src="Figures/pipeline" align="center" height="30%" width="30%" ></a>

## Claim Prioritisation

Strategies for integrating untrustworthy retrieved documents without relying on external evidence. We propose that such methods can fruitfully be combined with evidence-based reasoning, serving as a first line of defense and limiting expensive searches for additional evidence.

* Astute RAG: Overcoming Imperfect Retrieval Augmentation and Knowledge Conflicts for Large Language Models (Wang et al., 2025).
  [[Paper]](https://arxiv.org/abs/2410.07176).
* To Trust or Not to Trust? Enhancing Large Language Models' Situated Faithfulness to External Contexts (Huang et al., 2025).
  [[Paper]](https://openreview.net/forum?id=K2jOacHUlO).
* Why So Gullible? Enhancing the Robustness of Retrieval-Augmented Models against Counterfactual Noise (Hong et al., 2024).
  [[Paper]](https://aclanthology.org/2024.findings-naacl.159/)
* 


## Evidence Retrieval

* Corrective Retrieval Augmented Generation (Yan et al., 2024)
  [[Paper]](https://arxiv.org/abs/2401.15884)
* Certifiably Robust RAG against Retrieval Corruption (Xiang et al., 2024)
  [[Paper]](https://arxiv.org/abs/2405.15556)
*  

## Source Criticism

* Generating Media Background Checks for Automated Source Critical Reasoning
 (Schlichtkrull et al., 2023)
  [[Paper]](https://aclanthology.org/2024.findings-emnlp.283/)

## Veracity Analysis

## Datasets

* Can LLMs be Scammed? A Baseline Measurement Study (Sehwag et al., 2024).
  [[Paper]](https://arxiv.org/abs/2410.13893)
