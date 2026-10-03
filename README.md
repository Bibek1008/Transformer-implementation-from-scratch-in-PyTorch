
# Transformer From Scratch

A PyTorch implementation of the **Transformer architecture** introduced in
*Attention Is All You Need*, built by implementing the major Transformer
components directly rather than relying on a high-level Transformer module.

The project trains an encoder-decoder Transformer for **English → Italian
machine translation** using the OPUS Books dataset.

## Overview

The project implements the complete sequence-to-sequence Transformer pipeline:

```text
English Sentence
      ↓
Source Tokenizer
      ↓
Token Embeddings
      ↓
Positional Encoding
      ↓
Transformer Encoder
      ↓
Transformer Decoder
      ↓
Linear Projection
      ↓
German Sentence