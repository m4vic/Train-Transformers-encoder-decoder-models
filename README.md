# Train Transformer encoder and decoder
**From-Scratch Encoder & Decoder Transformer Models**

---

## Overview

**Transformer-101** contains from-scratch implementations of **Transformer encoder-only and decoder-only architectures**, trained, evaluated, and released publicly.

The project focuses on understanding Transformer internals at an **architecture level**, rather than building a production-scale LLM.

---

## Models Included

### 🔹 Encoder-Only Transformer (Classification)
- Task: Text classification  
- Dataset: **AG News**  
- Architecture: Transformer encoder  
- Trained end-to-end from scratch  

**Model:**  
🤗 https://huggingface.co/m4vic/agnews-transformer-encoder

---

### 🔹 Decoder-Only Transformer (GPT-style Generation)
- Task: Autoregressive text generation  
- Dataset: WikiText-103  
- Architecture: Transformer decoder with causal masking  

**Model:**  
🤗 https://huggingface.co/m4vic/MiniGPT-Wiki103

---

## Key Details

- Multi-head self-attention implemented manually  
- Positional encoding from scratch  
- Encoder and decoder trained independently  
- Training, evaluation, and experiments included  
- No prebuilt Transformer blocks used  

Each model has its own sub-README with full details.

---

## Educational Context

This project was built as a deep dive into Transformer internals.  
A full encoder walkthrough (math + code) is explained on a YouTube channel (Hindi).

---

## Scope

- Educational & research-focused  
- Not optimized for large-scale production  
- Designed for clarity and experimentation  

---

## Structure

transformer-101/
├── encoder/
├── decoder/
└── README.md
