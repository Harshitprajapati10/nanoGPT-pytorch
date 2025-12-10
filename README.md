# NanoGPT-PyTorch  
*A implementation of Bigram LM, Self-Attention, and Transformer models trained on Tiny Shakespeare.*

---

## 📘 Description

This repository provides a clean, step-by-step PyTorch implementation of a **nanoGPT-style character-level language model**.  
It begins with the simplest **Bigram Language Model**, then introduces **Self-Attention**, and finally builds a full **Transformer (GPT-style)** architecture.

The project is built for learning the internal working of modern LLMs with a readable, compact codebase.  
Dataset used: **Tiny Shakespeare** (~1MB of text).

---

## 📂 Features

### ✔️ Bigram Character-Level Model  
A simple model predicting the next character from the previous one.

**Concepts:**
- Character-level vocabulary  
- Token/char embeddings  
- Logits → softmax → cross-entropy  
- Baseline LM for comparison  

---

### ✔️ Self-Attention Mechanism  
The core idea behind modern Transformers.

**Includes:**
- Scaled dot-product attention  
- Causal masking (autoregressive)  
- Multi-Head Attention  
- Query–Key–Value projections  
- Attention weights via softmax  

---

### ✔️ Transformer Architecture  
A powerful GPT-style miniature model.

**Components:**
- Token & Positional embeddings  
- Multi-Head Self-Attention  
- Feedforward MLP layers  
- LayerNorm  
- Residual connections  
- Auto-regressive text generation  
- Training with AdamW & LR scheduling  

---


---

## 🧠 Model Progression

### **1️⃣ Bigram Model**
A minimal LM predicting the next token from the current one.

Learns:
- Basic statistics of character transitions  
- Vocabulary embeddings  
- Cross-entropy loss computation  

---

### **2️⃣ Self-Attention**
Introduces sequence awareness.

Learns:
- Token relationships  
- How to focus on important positions  
- Multiple attention "heads" for patterns  

---

### **3️⃣ Transformer**
A complete GPT-like model.

Features:
- Stacked attention blocks  
- Positional embeddings  
- Feedforward MLP  
- LayerNorm + residual pathways  
- Autoregressive text generation  

---


