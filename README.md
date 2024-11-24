# Abstractive Text Summarization for Indonesian News Article

This repository contains a lightweight abstractive text summarization system tailored for Indonesian news articles. The project leverages [mT5](https://huggingface.co/models) and [mBART-50](https://huggingface.co/facebook/mbart-large-50) models with [LoRA (Low-Rank Adaptation)](https://arxiv.org/abs/2106.09685) to enable efficient fine-tuning and deployment.

---

## Features

- **Language Support**: Focused on Indonesian-language news articles.
- **Models**:
  - **mT5**: Masks spans of text with unique tokens and learns to generate it using the surrounding context
  - **mBART-50**: Applies multiple noise types and learns to reconstruct the original text from the corrupted input
- **Efficiency**: LoRA reduces the number of trainable parameters, making the system lightweight and efficient.
- **Evaluation**: Includes metrics like ROUGE for assessing summarization quality.

---
