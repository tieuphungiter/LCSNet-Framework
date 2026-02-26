# 🌾 LCSNet–FedPerGC  
## Efficient Federated Learning Framework for Rice Leaf Disease Classification

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

---

## 📌 Abstract

Rice leaf disease classification under distributed data settings requires strict data privacy preservation and timely decision support across geographically dispersed agricultural regions, closely reflecting practical rice cultivation conditions in Vietnam.

In this work, we propose an end-to-end federated learning framework that integrates a lightweight deep learning backbone with an optimized federated optimization strategy. We introduce a compact convolutional neural network family, termed **LCSNet**, designed for efficient feature extraction with high classification accuracy and fast inference.

---

## 🔑 Keywords

- Rice disease classification  
- Federated Learning  
- Lightweight CNN  
- Non-IID data  
- Edge computing  
- LCSNet  
- FedPerGC  

---

## 🧠 Framework Overview

### 1️⃣ LCSNet – Lightweight CNN Backbone

LCSNet is a compact CNN family designed for:

- Efficient feature extraction  
- Low computational complexity  
- Real-time inference  
- Edge-device deployment  

#### 🔹 Performance Summary

| Model      | Accuracy | Inference Speed |
|------------|----------|----------------|
| LCSNet_3   | 95.44%   | > 330 FPS      |

---

### 2️⃣ FedPerGC – Federated Optimization Strategy

FedPerGC  enhances traditional federated learning by introducing:

- Gradient similarity analysis  
- Contribution-aware weighted aggregation  
- Stabilized convergence under non-IID distributions  

FedPerGC  consistently outperforms:

- FedAvg  
- FedAdam  
- FedProx  
- Baseline FedPer  

Across both IID and Non-IID settings.

---

### 3️⃣ Edge-AI Multi-Agent Client System

The system includes a client-side AI module that:

- Integrates federated model predictions  
- Combines contextual agricultural data  
- Supports real-time field-level decision making  

---

## 🏗 Architecture Details

The repository provides detailed model specifications including:

- Layer-by-layer architecture definitions  
- Activation functions  
- Dropout configurations  
- CBAM placement (where applicable)  
- Hyperparameter settings  

These details are implemented directly in the model source files to ensure full reproducibility.

---

## 📂 Repository Structure
