# Minimal GPT-2 Implementation

This project demonstrates the implementation and training of a **small GPT-2 model** from scratch to understand transformer internals and practical language model training.

---

## Project Summary

Built and trained a **minimal GPT-2 model** on a small dataset (~300,000 tokens) to explore the key components of transformer-based language models. This project helped in understanding:

- BPE-based tokenization  
- Token and positional embeddings  
- Multi-head self-attention and decoder blocks  
- Causal masking and training loops  
- Generating text from a trained model  

---

## Work Completed ✅

- Implemented **BPE-based tokenization** for input text.  
- Built **token embeddings** and **positional embeddings**.  
- Scaffolded **modular GPT-2 components** including attention and feed-forward layers.  
- Implemented **multi-head self-attention** with causal masking.  
- Built **transformer decoder blocks** with residual connections and layer normalization.  
- Implemented **training loop** with cross-entropy loss and evaluation metrics.  
- Successfully trained the model on a **small dataset (~300k tokens)**.  
- Generated **meaningful sample text** from the trained model.

---

## Next Steps / Improvements 🛠️

- Scale training to **larger datasets**.  
- Fine-tune **hyperparameters** for better text generation quality.  
- Integrate **advanced sampling strategies** (top-k, top-p).  
- Deploy the trained model for **real-world text generation applications**.  

---

## Dataset

- Used a small dataset of ~300,000 tokens (example: The verdict).  
- Split into **90% training** and **10% validation**.  

---

## Model Architecture

- **Vocabulary size:** 50257  
- **Embedding dimension:** 768  
- **Context length:** 256 tokens  
- **Number of layers:** 12  
- **Number of attention heads:** 12  
- **Dropout:** 0.1  
- **Optimizer:** AdamW  
- **Learning rate:** 5e-4  

---

## Usage

1. Clone the repository:
```bash
git clone <repo-url>
cd <repo-name>
