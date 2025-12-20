---
title: "LLM-Enhanced Cross-Domain Graph Neural Networks"
excerpt: "Zero-shot GNN generalization framework leveraging large language models for semantic alignment across heterogeneous domains"
collection: portfolio
---

## Overview
This research project addresses the challenge of transferring Graph Neural Network (GNN) models across different domains without labeled data. I propose a novel framework that leverages Large Language Models (LLMs) to provide semantic priors for node and edge alignment in heterogeneous graph structures.

## Problem Statement
Cross-domain generalization in GNNs faces a critical bottleneck: semantic misalignment between source and target domains. Traditional transfer learning approaches require labeled data in the target domain, which is often expensive or unavailable.

## Approach
- **LLM-Based Semantic Priors**: Utilize pre-trained language models to generate textual descriptions for graph nodes and edges
- **Zero-Shot Transfer**: Enable label-free domain adaptation by aligning semantic spaces across domains
- **Hybrid Framework**: Combine LLM-based textual embeddings with traditional GNN embeddings
- **Literature Foundation**: Built upon recent advances in LLM-TTT, GraphCL, GraphPrompt, and zero-shot graph learning

## Key Contributions
1. Identified semantic misalignment as the key bottleneck in cross-domain heterogeneous GNN generalization
2. Designed a conceptual framework combining LLM semantic knowledge with graph structural information
3. Demonstrated improved feature transfer performance in unlabeled target domains through preliminary experiments
4. Proposed a low-cost alternative to traditional fine-tuning approaches

## Status
**Ongoing Research** (Jan 2025 – Present)

Preliminary experiments show promising results in improving cross-domain transfer without requiring labeled target domain data.

## Technologies
- **Frameworks**: PyTorch, PyTorch Geometric
- **Models**: Graph Neural Networks (GCN, GAT, HGT), Large Language Models
- **Techniques**: Zero-shot learning, semantic alignment, graph representation learning
