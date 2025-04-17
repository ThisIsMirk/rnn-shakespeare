# Tiny Shakespeare RNN Text Generation

This project explores character-level text generation using Recurrent Neural Networks (RNNs) on the Tiny Shakespeare dataset. The notebook demonstrates training of different RNN architectures (Vanilla RNN, LSTM, GRU) with bidirectional layers and embedding representations, comparing their performance through perplexity scores.

## Features

- Implements **Vanilla RNN**, **LSTM**, and **GRU** using PyTorch.
- Supports **bidirectional layers** and **embedding layers** for efficient training.
- Tokenization handled using **Byte Pair Encoding (BPE)** with the `tokenizers` library.
- Includes functions for training, validation, and perplexity-based evaluation.
- Data split and training strategy optimized for sequence learning.

## Model Evaluation

- Trained on Tiny Shakespeare dataset with reduced epochs for experimentation.
- Evaluates models using **perplexity** on a held-out test set.

## Requirements

- `torch`
- `tokenizers`
- `numpy`
- `matplotlib`

## How to Use

1. Load and preprocess the Tiny Shakespeare dataset.
2. Tokenize the text using BPE.
3. Choose a model (RNN, LSTM, GRU), then train and evaluate.
4. Use `generate_text()` function to sample Shakespeare-like text.
