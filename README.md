# Lora_fintuning
# LoRA Fine-Tuning on GPT-2 using HuggingFace Transformers

This project demonstrates how to fine-tune the `gpt2-large` language model using Low-Rank Adaptation (LoRA) with the HuggingFace `transformers`, `peft`, and `datasets` libraries.

The goal is to adapt GPT-2 to specific text data (e.g., on Akhenaten) using parameter-efficient fine-tuning with LoRA.

## 🧠 Technologies Used

- HuggingFace Transformers
- HuggingFace Datasets
- PEFT (Parameter-Efficient Fine-Tuning)
- Google Colab
- PyTorch

---

## 📦 Installation

Install the required dependencies:

```bash
pip install transformers peft datasets
pip install --upgrade datasets huggingface-hub fsspec
