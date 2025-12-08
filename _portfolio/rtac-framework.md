---
title: "RTaC: Reasoning through Tool-based Action Chains"
collection: portfolio
permalink: /portfolio/rtac-framework
excerpt: "Framework for training LLMs to effectively sequence tool usage for complex multi-step reasoning tasks"
date: 2024-06-01
---

## Overview

RTaC is a novel framework for training Large Language Models (LLMs) to reason through complex tasks by sequencing tool usage. Instead of one-shot tool calls, RTaC teaches models how to chain multiple tools strategically to solve problems requiring multi-step reasoning.

## Key Contributions

- **Novel Training Framework**: Developed methodology for teaching LLMs effective tool sequencing
- **Fine-tuned Models**: Successfully fine-tuned CodeLlama-7B and DeepSeek-1.3B on RTaC data
- **Performance Gains**: Achieved strong performance on reasoning benchmarks with 90% fewer tokens than GPT-4
- **Cost Optimization**: Reduced inference cost by 85% while maintaining competitive accuracy
- **Published Research**: First-author paper published on LLM tool usage sequencing

## Technologies Used

- Python (PyTorch, Hugging Face Transformers)
- LLM Fine-tuning (LoRA, QLoRA)
- Chain-of-Thought prompting
- Tool integration and orchestration
- Evaluation on reasoning benchmarks (GSM8K, MATH, HumanEval)

## Results

- Successfully demonstrated multi-step tool reasoning
- Outperformed larger models on specific task domains
- Published in peer-reviewed venue
- Framework applicable to various task domains

## Links

- [Research Paper](https://arxiv.org/)
- [GitHub Repository](https://github.com/NisargBhavsar25)