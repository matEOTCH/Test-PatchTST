# 📊 PatchTST for Time Series Forecasting

This repository contains an implementation of **PatchTST**, a Transformer-based model for **long-term time series forecasting**, inspired by the paper:

> *"A Time Series is Worth 64 Words: Long-Term Forecasting with Transformers"*

---

## 🚀 Overview

Time series forecasting is a critical task in many domains such as energy, finance, and industrial systems. Traditional Transformer models often struggle with long sequences due to computational complexity and lack of locality.

**PatchTST** addresses this by:

- Splitting time series into **patches**
- Applying **Transformer encoders** to patches instead of raw sequences
- Improving efficiency and long-term forecasting performance

---

## 🧠 Key Concepts Implemented

- Sliding Window preprocessing
- Patch creation (temporal segmentation)
- Patch Embedding
- Transformer Encoder
- Instance Normalization
- Forecasting Head

---

## ⚙️ Methodology

The pipeline followed in this project:

1. **Data preprocessing**
2. Creation of **sliding windows**
3. Division into **overlapping patches**
4. Input into **Transformer model**
5. Training using loss functions:
   - Mean Squared Error (MSE)
6. Evaluation using:
   - MSE
   - Mean Absolute Error (MAE)

---

## 📊 Results

The model was evaluated using training and validation loss curves, as well as forecasting visualizations.

Key observations:

- Training loss decreases consistently
- Validation loss shows generalization behavior
- Model captures temporal patterns effectively

---

## 🧪 Experimentation

Experiments include:

- Different window sizes
- Patch lengths and strides
- Training epochs and learning rates

---

## 📁 Project Structure
