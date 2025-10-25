# 🧠 PyTorch Research Implementations — From First Principles

This repository serves as a **technical index** of my deep learning architectures implemented from scratch using pure **PyTorch**.  
Each implementation recreates a foundational AI paper from the ground up — without high-level wrappers — to deeply understand the mathematical and computational mechanics behind modern neural architectures.

---

## 🎯 Objective

To **rebuild cornerstone deep learning architectures from first principles** — verifying equations, coding them tensor-by-tensor, and ensuring reproducibility in PyTorch.  
This series represents hands-on replication of seminal research papers across three fundamental areas of deep learning:

- **Sequence Modeling & Attention**
- **Graph Neural Networks**
- **Deep Convolutional Networks**

---

## 📚 Implemented Architectures and Papers

| # | Model | Research Paper | Description | Repository |
|---|--------|----------------|--------------|-------------|
| 1️⃣ | **RNN + LSTM + Bahdanau Attention** | *Neural Machine Translation by Jointly Learning to Align and Translate*<br>Bahdanau, Cho & Bengio (ICLR 2015)<br>[arXiv:1409.0473](https://arxiv.org/abs/1409.0473) | Modular attention mechanism with bidirectional LSTM support for sequence modeling tasks. | [🔗 Repository](link-to-repo) |
| 2️⃣ | **GCN (Graph Convolutional Network)** | *Semi-Supervised Classification with Graph Convolutional Networks*<br>Kipf & Welling (ICLR 2017)<br>[arXiv:1609.02907](https://arxiv.org/abs/1609.02907) | Manual adjacency normalization and spectral message passing without `torch_geometric.nn`. | [🔗 Repository](link-to-repo) |
| 3️⃣ | **ResNet (Residual Network)** | *Deep Residual Learning for Image Recognition*<br>He, Zhang, Ren & Sun (CVPR 2016)<br>[arXiv:1512.03385](https://arxiv.org/abs/1512.03385) | Residual blocks with projection shortcuts and dataset-agnostic training pipeline. | [🔗 Repository](link-to-repo) |

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
| Sequence Modeling | RNN, LSTM, Attention | Temporal dependencies, soft alignment mechanisms |
| Graph Learning | GCN | Spectral message passing, adjacency normalization |
| Computer Vision | ResNet | Residual learning, gradient flow preservation |

---

## 🧠 Future Work

| Upcoming Model | Paper | Focus |
|----------------|--------|--------|
| **GAT (Graph Attention Network)** | Veličković et al., ICLR 2018 | Attention-based neighbor weighting |
| **GraphSAGE** | Hamilton et al., NeurIPS 2017 | Inductive graph representation learning |
| **Transformer** | Vaswani et al., NeurIPS 2017 | Multi-head self-attention mechanisms |

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
