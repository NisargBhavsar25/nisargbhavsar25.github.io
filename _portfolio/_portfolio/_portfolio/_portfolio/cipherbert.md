---
title: "CipherBERT: Privacy-Preserving NLP with Homomorphic Encryption"
collection: portfolio
permalink: /portfolio/cipherbert
excerpt: "Homomorphic encryption framework for privacy-preserving text classification and NLP inference"
date: 2024-12-01
---

## Overview

CipherBERT is a novel framework that enables privacy-preserving NLP inference using fully homomorphic encryption (FHE). This work demonstrates how BERT-like models can perform text classification on encrypted data without decryption.

## Key Contributions

- **Privacy-Preserving Inference**: First application of FHE to BERT for end-to-end encrypted inference
- **IEEE Publication**: Accepted to IEEE Transactions on Power Systems (TPS) 2025
- **Practical Benchmarks**: Evaluated on real text classification datasets
- **Security Analysis**: Formal security proofs for data privacy guarantees
- **Efficiency Improvements**: Optimized FHE operations for faster encrypted inference

## Technologies Used

- Python, PyTorch, Hugging Face Transformers
- SEAL (Simple Encrypted Arithmetic Library) for FHE
- BERT and DistilBERT architectures
- Homomorphic Encryption schemes
- Security analysis and cryptographic proofs

## Results

- Demonstrated encrypted inference with <5% accuracy loss
- Generated practical security parameters for deployment
- Evaluated on multiple text classification benchmarks
- Published in IEEE TPS 2025

## Links

- [IEEE Publication](https://ieeexplore.ieee.org/)
- [GitHub Implementation](https://github.com/NisargBhavsar25/CipherBERT)