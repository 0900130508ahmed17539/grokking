# Grokking in Neural Networks

## Overview

Typically, as a neural network's performance on training data improves, its performance on unseen validation data also improves until the network starts overfitting. However, grokking, a recently discovered phenomenon, defies this norm by showing a sudden and dramatic improvement in validation performance long after overfitting has begun. This delayed generalization pattern has been notably observed in algorithmic tasks like modular addition. Grokking is sometimes viewed as a phase change in the network's learning process.

## Project Description

In this project, we explore the concept of grokking in the context of modular addition, examining its occurrence in different types of neural networks and training setups. We discovered that grokking happens in many types of models and is influenced by the amount of training data used. Specifically, we conduct our experiments in recurrent neural networks (RNNs) and long short-term memory (LSTM) networks.

## Key Findings

1. **Impact of Training Data**: Grokking is influenced by the amount of training data used.
2. **Regularization Techniques**: Our results show that using regularization techniques such as weight decay can help the models generalize better.
3. **Weight Decay**: 
    - Training without weight decay leads to poor generalization.
    - Removing weight decay too early also results in suboptimal performance.
    - Weight decay is not necessary during the early phases of training.
    - Introducing weight decay only late in training still leads to grokking, which is a novel discovery.

## Goals

These experiments aim to provide deeper insights into the factors that affect grokking and to optimize training strategies for better model generalization.


