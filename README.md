# 🧠 PyTorch Research Implementations — From First Principles

This repository serves as a **technical index** of my deep learning architectures implemented from scratch using pure **PyTorch**.  
Each implementation recreates a foundational AI paper from the ground up — without high-level wrappers — to deeply understand the mathematical and computational mechanics behind modern neural architectures.

---

## 🎯 Objective

To **rebuild cornerstone deep learning architectures from first principles** — verifying equations, coding them tensor-by-tensor, and ensuring reproducibility in PyTorch.  
This series represents hands-on replication of seminal research papers across three fundamental areas of deep learning:

- **Sequence Modeling & Attention**
- **Transformer Architectures**
- **Graph Neural Networks**
- **Deep Convolutional Networks**

---

## 📚 Implemented Architectures and Papers

| # | Model | Research Paper | Description | Repository |
|---|--------|----------------|--------------|-------------|
| 1️⃣ | **Transformer (Attention Is All You Need)** | *Attention Is All You Need*<br>Vaswani et al. (NeurIPS 2017)<br>[arXiv:1706.03762](https://arxiv.org/abs/1706.03762) | Multi-head scaled dot-product attention, sinusoidal positional encoding, encoder-decoder stacks with masking and layer normalization. | [🔗 Repository](https://github.com/arnavmishra4/Transformer-Attention-Is-All-You-Need-From-Scratch-in-PyTorch) |
| 2️⃣ | **GNN (Graph Neural Networks)** | *Semi-Supervised Classification with Graph Convolutional Networks*<br>Kipf & Welling (ICLR 2017)<br>*Graph Attention Networks*<br>Veličković et al. (ICLR 2018)<br>*Inductive Representation Learning on Large Graphs*<br>Hamilton et al. (NeurIPS 2017) | GCN with manual adjacency normalization, GAT with multi-head attention mechanisms, and GraphSAGE with inductive neighborhood sampling. | [🔗 Repository](https://github.com/arnavmishra4/From-GCNs-to-GraphSAGE-Graph-Neural-Networks-from-Scratch-in-PyTorch) |
| 3️⃣ | **ResNet (Residual Network)** | *Deep Residual Learning for Image Recognition*<br>He, Zhang, Ren & Sun (CVPR 2016)<br>[arXiv:1512.03385](https://arxiv.org/abs/1512.03385) | Residual blocks with projection shortcuts and dataset-agnostic training pipeline. | [🔗 Repository](https://github.com/arnavmishra4/ResNet-from-Scratch-Deep-Residual-Learning-in-PyTorch) |
| 4️⃣ | **RNN + LSTM + Bahdanau Attention** | *Neural Machine Translation by Jointly Learning to Align and Translate*<br>Bahdanau, Cho & Bengio (ICLR 2015)<br>[arXiv:1409.0473](https://arxiv.org/abs/1409.0473) | Encoder-decoder architecture with additive attention mechanism, implementing hidden state alignment and dynamic context weighting from scratch. | [🔗 Repository](https://github.com/arnavmishra4/From-RNNs-to-Bahdanau-Attention-A-Research-Level-Implementation-in-PyTorch) |

---

## 🧩 Design Philosophy

Each implementation follows a **modular, research-grade structure**:
- Every layer and computation is defined explicitly (no hidden abstractions)
- Architectures are decomposed into reusable `models/`, `data_loader/`, and `config/` modules
- Each repository mirrors a research lab codebase — clear, extendable, and reproducible

> *"I don't just read papers — I rebuild them, line by line, to understand why they work."*

---

## 🧮 Research Areas Covered

| Domain | Architecture | Focus |
|---------|--------------|--------|
| Transformer Architectures | Multi-Head Self-Attention | Parallelized attention, positional encoding |
| Graph Learning | GCN, GAT, GraphSAGE | Spectral/attention-based message passing, inductive learning |
| Computer Vision | ResNet | Residual learning, gradient flow preservation |
| Sequence Modeling | RNN, LSTM, Bahdanau Attention | Temporal dependencies, additive attention alignment |

---

## 🧠 Future Work

| Upcoming Model | Paper | Focus |
|----------------|--------|--------|
| **Vision Transformer (ViT)** | Dosovitskiy et al., ICLR 2021 | Transformer-based image classification |
| **Diffusion Models** | Ho et al., NeurIPS 2020 | Denoising diffusion probabilistic models |

---

## 🧰 Technical Stack

All implementations use:
- **PyTorch** for tensor operations and autograd
- **Dataset-agnostic training** (ImageFolder for vision, PyG Data for graphs, custom loaders for sequences)
- **Modular pipelines** (`main.py`, `config.py`, `data_loader.py`)

---

## 🏁 Author

**Arnav Mishra**  
AI Researcher · PyTorch & Deep Learning  
Bhopal, India

---

> *"Understanding an architecture means being able to rebuild it from nothing but the paper."*
