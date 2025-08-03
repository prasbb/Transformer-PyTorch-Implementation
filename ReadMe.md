# 🧠 Transformer Architecture from Scratch (PyTorch)

This project is a clean, educational implementation of the **Transformer architecture** (as introduced in [Attention is All You Need](https://arxiv.org/abs/1706.03762)), built entirely in **PyTorch**.

---

## Architecture

The implementation follows the classic Transformer design:

- **Input Embedding + Positional Encoding**
- **N × Encoder Layers**  
  - Multi-head Self-Attention  
  - Feed-Forward Network  
  - Layer Normalization + Residuals
- **N × Decoder Layers**  
  - Masked Multi-head Self-Attention  
  - Encoder-Decoder Attention  
  - Feed-Forward Network
- **Final Linear + Softmax Layer**

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Framework:** PyTorch  

