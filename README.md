# DL Project 2: LoRA on RoBERTa for AGNEWS Classification

This project is part of NYU's Spring 2025 Deep Learning course. We finetuned a frozen `roberta-base` model using Low-Rank Adaptation (LoRA) to classify AGNEWS headlines under a strict 1M trainable parameter constraint.

---

## Final Results
- **Validation Accuracy:** 92.81%
- **Trainable Parameters:** 925,444
- Trained for 4 epochs with cosine decay, warmup 0.1

---

## Requirements
```bash
pip install transformers datasets peft evaluate accelerate
