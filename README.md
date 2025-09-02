# LLM Safety Techniques

This repository serves as a structured chronological survey of Large Language Model (LLM) safety techniques. Each technique is documented with a summary outlining the algorithm and contrasting it with other approaches.

## Table of Contents
1. [OpenAI Harmony Protocol](#1-openai-harmony-protocol)
2. [Anthropic's Constitutional AI](#2-anthropic-constitutional-ai)
3. [Google's AI Safety Framework](#3-google-ai-safety-framework)
4. [Meta's Safety Approaches](#4-meta-safety-approaches)
5. [Open Source AI Safety Implementations](#5-open-source-ai-safety-implementations)

## 1. OpenAI Harmony Protocol

A structured communication protocol for OpenAI's gpt-oss open-weight models that enables multi-channel interactions, transparent chain-of-thought reasoning, and advanced tool calling.

- [Overview and Analysis](articles/openai-harmony.md)
- [OpenAI Harmony Response Format | OpenAI Cookbook](https://cookbook.openai.com/articles/openai-harmony)
- [openai-harmony · PyPI](https://pypi.org/project/openai-harmony/)
- [GitHub - openai/harmony](https://github.com/openai/harmony)
- [GitHub - mbrukman/openai-harmony](https://github.com/mbrukman/openai-harmony)
- [What is GPT OSS Harmony Response Format?](https://cobusgreyling.medium.com/what-is-gpt-oss-harmony-response-format-a29f266d6672)

## 2. Anthropic's Constitutional AI

A two-phase training process combining supervised learning with constitutional principles and Reinforcement Learning from AI Feedback (RLAIF) to create models that are both more helpful and more harmless.

- [Overview and Analysis](articles/anthropic-constitutional-ai.md)
- [Constitutional AI: Harmlessness from AI Feedback](https://www.anthropic.com/research/constitutional-ai-harmlessness-from-ai-feedback)
- [Constitutional AI - PRIMO.ai](https://primo.ai/index.php?title=Constitutional_AI)
- [What is Constitutional AI (CAI)? - Zilliz Learn](https://zilliz.com/learn/constitutional-ai-harmlessness-from-ai-feedback)
- [Claude's Constitution](https://www.anthropic.com/news/claudes-constitution)
- [Understanding Constitutional AI](https://medium.com/@jonnyndavis/understanding-constitutional-ai-dd9d783ef712)
- [Constitutional Classifiers: Defending against universal jailbreaks](https://www.anthropic.com/news/constitutional-classifiers)

## 3. Google's AI Safety Framework

A proactive approach to identifying Critical Capability Levels (CCLs) with Google's Secure AI Framework (SAIF) and Frontier Safety Framework.

- [Overview and Analysis](articles/google-ai-safety-framework.md)
- [Google's Secure AI Framework - Google Safety Center](https://safety.google/cybersecurity-advancements/saif/)
- [Introducing the Frontier Safety Framework](https://deepmind.google/discover/blog/introducing-the-frontier-safety-framework/)

## 4. Meta's Safety Approaches

A multi-layered safety approach including the open-source Llama Guard system for content moderation and extensive red-teaming exercises.

- [Overview and Analysis](articles/meta-safety-approaches.md)
- [Safeguarding Your RAG Pipelines: A Step-by-Step Guide to Implementing Llama Guard with LlamaIndex](https://towardsdatascience.com/safeguarding-your-rag-pipelines-a-step-by-step-guide-to-implementing-llama-guard-with-llamaindex-6f80a2e07756-2/)
- [The Dispatch Report: GitHub Repo Analysis: meta-llama/PurpleLlama](https://thedispatch.ai/reports/792/)

## 5. Open Source AI Safety Implementations

Various open-source implementations of AI safety techniques including Constitutional AI with Open LLMs and RLHF frameworks.

- [Overview and Analysis](articles/open-source-ai-safety.md)
- [Constitutional AI with Open LLMs](https://huggingface.co/blog/constitutional_ai)
- [GitHub - OpenRLHF/OpenRLHF: An Easy-to-use, Scalable and High-performance RLHF Framework](https://github.com/OpenRLHF/OpenRLHF)
- [[2405.11143] OpenRLHF: An Easy-to-use, Scalable and High-performance RLHF Framework](https://arxiv.org/abs/2405.11143)
- [GitHub - ottosulin/awesome-ai-security: A collection of awesome resources related AI security](https://github.com/ottosulin/awesome-ai-security)

---
*This survey is maintained as a chronological collection of LLM safety techniques, with each entry linking to both the original source and a detailed analysis in the articles directory.*
