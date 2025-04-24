# Transformer From Scratch: Emoji Translator 🧠➡️😊

This project is a minimal implementation of the legendary paper  
**"Attention Is All You Need"** — rebuilt from scratch in PyTorch.

## 🚀 What It Does
- Implements a Transformer (no HuggingFace, no shortcuts)
- Trains on toy data (English to emoji translation)
- Includes greedy decoding, beam search & top-k sampling
- Uses only basic PyTorch and torch.utils.data

## 🧱 Architecture
- Full encoder-decoder Transformer
- Multi-head attention, FFN, layer norm
- Custom tokenizer and dataloader
