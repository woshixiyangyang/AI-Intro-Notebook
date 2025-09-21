# AI-Intro-Notebook
人工智能概论课程作业与练习 | Notebooks for Introduction to Artificial Intelligence course
## 说明 / Explanation

本 Notebook 展示了用 PyTorch 从张量创建，到搭建、训练一个简单线性神经网络的全过程。

This notebook demonstrates the full process from tensor creation to building and training a simple linear neural network with PyTorch.

---

### 你在做什么 / What are you doing

- 创建张量（Tensor）作为输入输出数据。
- 定义最简单的线性模型：`Linear(2, 1)`。
- 使用 MSE 损失函数和 Adam 优化器。
- 通过训练，让模型学会将输入 [5, 3] 映射到输出 8。
- 每100步记录一次模型输出，最后画图查看收敛过程。

- Create tensors for input and output.
- Define the simplest linear model: `Linear(2, 1)`.
- Use MSE loss and Adam optimizer.
- Train the model to map input [5, 3] to output 8.
- Log outputs every 100 steps, plot to visualize convergence.

---

### 为什么要这样做 / Why

- 理解 PyTorch 基础操作和神经网络训练流程。
- 直观感受参数不断优化，输出逐步接近目标的过程。

- To understand PyTorch basics and the neural network training workflow.
- To see how parameters are optimized and outputs approach the target.

---

### 这样做以后会如何 / What will happen

- 你能用 PyTorch 独立实现基本的神经网络训练。
- 掌握深度学习“输入-模型-损失-优化”基本环节。

- You will be able to implement basic neural network training in PyTorch.
- You will master the core loop: input → model → loss → optimization.

---
