# Transformer-Based Text Classifier (Inspired by "Attention Is All You Need")

This repository implements a simplified Transformer encoder from scratch in PyTorch, for text classification tasks. The architecture follows the key ideas from the ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762) paper, including custom positional encoding and a self-attention mechanism.

##  Features

- Tokenization using HuggingFace BERT tokenizer
- Sinusoidal positional encoding (no pretrained embeddings used)
- Self-attention mechanism implemented from scratch
- Simple feed-forward classification head
- Custom training loop with per-batch loss and accuracy display
- Test mode to evaluate the model on any custom input text

---

##  Model Architecture

- **Embedding + Positional Encoding**
- **Self-Attention Block** (Single-head, basic implementation)
- **Global Average Pooling**
- **Feedforward Neural Net**
- **Softmax Output**

---
