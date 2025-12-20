---
title: "Drug Trafficker Social Network Analysis"
excerpt: "Large-scale heterogeneous graph dataset construction and analysis for understanding illicit drug trafficking networks on social media"
collection: portfolio
---

## Overview
This project focuses on constructing and analyzing a large-scale heterogeneous social network to understand the structure and behavior patterns of drug trafficking communities on social media platforms.

## Dataset Construction
Built a comprehensive multi-layer social network dataset:
- **7,000+** user profiles
- **45,000+** social media posts
- **500+** trafficking-related keywords
- **Multiple edge types**: replies, retweets, mentions, follower relationships

## Technical Highlights

### Data Collection
- Developed custom **Playwright-based web crawlers** to overcome Twitter API limitations
- Implemented multi-layer data collection strategy capturing user profiles, posts, and interaction patterns
- Designed bidirectional edge construction using replies and retweets to improve graph completeness

### Intelligent Labeling
- Created an **LLM-assisted semi-automatic labeling workflow** to reduce manual annotation costs
- Leveraged language models to identify trafficking-related content and user roles
- Significantly improved labeling efficiency while maintaining quality

### Model Evaluation
Benchmarked multiple state-of-the-art heterogeneous graph neural networks:
- **GCN** (Graph Convolutional Networks)
- **GAT** (Graph Attention Networks)
- **HAN** (Heterogeneous Attention Networks)
- **HetGNN** (Heterogeneous Graph Neural Networks)
- **HGAT** (Heterogeneous Graph Attention Networks)

## Tasks
1. **Node Classification**: Identifying user roles (trafficker, buyer, intermediary)
2. **Relation Prediction**: Predicting future connections and interactions
3. **Community Detection**: Uncovering trafficking networks and hierarchies

## Impact
This dataset and analysis framework can support:
- Law enforcement investigations
- Social media platform safety measures
- Academic research on online illicit activities

## Technologies
- **Data Collection**: Python, Playwright, RESTful APIs
- **Machine Learning**: PyTorch, PyTorch Geometric
- **Models**: GCN, GAT, HAN, HetGNN, HGAT
- **NLP**: Large Language Models for content analysis
