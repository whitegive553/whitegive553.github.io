---
title: "End-to-End Liquor Cabinet Bottle Recognition System (Patent Filed)"
excerpt: "Label-free batch bottle recognition system using ArcFace embeddings for real-world commercial deployment"
collection: portfolio
---

## Overview
Developed a production-ready bottle recognition system for liquor cabinet management in commercial environments. The system addresses real-world challenges such as weak lighting, cluttered backgrounds, and the need for easy updates without retraining.

**Status**: Patent Filed

## Problem Statement
Traditional product recognition systems face challenges in retail environments:
- **Lighting variations**: Weak or inconsistent lighting conditions
- **Visual clutter**: Overlapping bottles and complex backgrounds
- **Update overhead**: Adding new products requires costly model retraining
- **Unknown items**: Systems often misclassify unfamiliar bottles with high confidence

## Technical Solution

### ArcFace-Based Embedding Space
- Designed a robust feature embedding space using **ArcFace** loss function
- Achieves superior discrimination between similar bottle designs
- Maintains robustness under challenging lighting and clutter conditions

### Incremental Learning
- Implemented **embedding insertion** mechanism for adding new bottle types
- **No retraining required**: Simply add new bottle embeddings to the database
- Enables rapid deployment updates in production environments

### Open-Set Recognition
- Developed **unknown-class detection** to prevent misclassification of unfamiliar bottles
- System can confidently reject items it hasn't been trained on
- Critical for real-world deployment where new products constantly appear

### Benchmarking
Compared against state-of-the-art methods:
- **Baseline**: Softmax classification
- **Ours**: Softmax + ArcFace
- **SOTA**: Proser and other open-set recognition methods

Our approach demonstrated superior performance in both closed-set and open-set scenarios.

## Key Features
1. **Label-free recognition**: Works with unlabeled bottle images
2. **Batch processing**: Efficiently handles multiple bottles simultaneously
3. **Production-ready**: Designed for real-world commercial deployment
4. **Scalable**: Easy to add new products without model retraining
5. **Robust**: Handles challenging lighting and background conditions

## Applications
- Liquor cabinet inventory management
- Retail product recognition
- Smart refrigerator systems
- Automated checkout systems

## Technologies
- **Deep Learning**: PyTorch, ArcFace loss
- **Computer Vision**: Object detection, feature extraction
- **Deployment**: Docker, RESTful APIs
- **Comparison Methods**: Softmax baseline, Proser, open-set recognition

## Affiliation
Developed at **HuleTech**, Prof. Yijie Peng's Group, Peking University (May 2025 – Aug 2025)
