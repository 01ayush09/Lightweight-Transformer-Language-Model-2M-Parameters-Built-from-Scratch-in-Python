# Design and Implementation of a 2M+ Parameter Transformer Language Model from Scratch in Python

## 📌 Overview

This project demonstrates the **end-to-end design, implementation, and training of a lightweight Transformer-based language model (~2.3M parameters) built entirely from scratch using Python**. The goal of this project is to deeply understand the **internal mechanics of modern Large Language Models (LLMs)** by implementing every core component without relying on deep learning frameworks such as PyTorch or TensorFlow.

The model is inspired by **LLaMA-style architectures** and includes modern Transformer design choices such as **RMSNorm, Rotary Positional Embeddings (RoPE), and SwiGLU feed-forward layers**.

---

## 🎯 Objectives

* Understand Transformer architectures at a **low-level, implementation-first** perspective
* Build a **fully functional language model** using only Python and NumPy
* Explore how modern LLM components work together during **training and inference**
* Demonstrate strong fundamentals in **deep learning, linear algebra, and NLP**

---

## 🧠 Model Architecture

* **Decoder-only Transformer** (LLaMA-inspired)
* **~2.3M trainable parameters**
* **Multi-Head Self-Attention** with causal masking
* **Rotary Positional Embeddings (RoPE)**
* **RMSNorm** instead of LayerNorm
* **SwiGLU** activation in feed-forward layers
* **Token and output embedding weight tying**

---

## ⚙️ Key Components Implemented from Scratch

* Custom **tokenization and vocabulary handling**
* Embedding layers
* Multi-head self-attention
* Causal attention masking
* RMSNorm
* SwiGLU feed-forward networks
* Transformer block stacking
* Forward and backward pass logic
* Loss computation (cross-entropy)
* Training loop and evaluation
* Text generation (autoregressive decoding)

---

## 🛠️ Tech Stack

* **Python**
* **NumPy**
* No deep learning frameworks used

---

## 📊 Training Details

* Trained on a small-scale text corpus
* Autoregressive next-token prediction objective
* Designed for **educational clarity**, not large-scale deployment

---

## 🚀 Why This Project Matters

Most LLM projects rely heavily on high-level libraries. This project stands out by:

* Showing **deep understanding of Transformer internals**
* Demonstrating ability to **build neural architectures from first principles**
* Providing strong evidence of **ML engineering and NLP fundamentals**

This makes it particularly valuable for:

* ML Engineer / NLP Engineer roles
* Research-oriented internships
* Academic or learning-focused portfolios

---

## 🔮 Future Improvements

* Scaling to larger parameter counts
* Adding Byte Pair Encoding (BPE) or SentencePiece tokenization
* Training on larger and more diverse datasets
* GPU acceleration
* Converting implementation to PyTorch/JAX for benchmarking

---

## 📎 Acknowledgements

Inspired by modern Transformer and LLaMA-style architectures, with a focus on learning through implementation.

---

⭐ If you find this project useful for learning or reference, feel free to star the repository!
