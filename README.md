# Victor Wu — Machine Learning & Data Science Portfolio

I build and analyze machine learning systems end-to-end — from data preprocessing
and modeling to evaluation and interpretation.

This portfolio highlights selected projects demonstrating:
- reinforcement learning
- neural network modeling
- applied data analysis
- reproducible ML engineering practices

## Transformer Next-Token Predictor

**Tech:** PyTorch, Transformers, Autoregressive Language Modeling  
**Focus:** Neural architectures, representation learning

A small transformer-based next-token prediction model inspired by modern language
models. I implemented tokenization, attention blocks, masking, and training loops
from scratch to understand the mechanics behind large language models.

Key aspects:
- causal self-attention with masking
- custom training loop and loss tracking
- comparison of depth/width tradeoffs

**Code:** https://github.com/VictorWuuuuuu/Transformer-v1


## Double DQN Agent — Atari Donkey Kong

**Tech:** PyTorch, Gymnasium (ALE), Double DQN, Experience Replay  
**Focus:** Reinforcement learning, stability, training dynamics

I implemented a Double Deep Q-Network agent to play Atari Donkey Kong, using
grayscale preprocessing, frame stacking, experience replay, and a target network
to reduce overestimation bias.

Key aspects:
- online vs target network separation (DDQN)
- epsilon-greedy exploration with linear decay
- checkpointing and resumable training
- evaluation via GIF-rendered episodes

**Code:** https://github.com/VictorWuuuuuu/DonkeyKongRL
