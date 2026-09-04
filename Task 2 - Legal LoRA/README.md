
# Task 2 — Legal Contract Clause Classification using LoRA

## Overview

This project focuses on **domain-specific fine-tuning of Qwen2.5-7B-Instruct using LoRA** for legal contract clause classification.

The model was fine-tuned using the **CUAD (Contract Understanding Atticus Dataset)** containing 41 legal clause categories.

The fine-tuned model is named **LexAI-LoRA**.

## Technologies

- Python
- Google Colab
- Qwen2.5-7B-Instruct
- Unsloth
- LoRA / QLoRA
- Hugging Face Datasets
- PyTorch

## Results

- **Accuracy:** 58.81%
- **Weighted F1 Score:** 57.92%
- **Trainable Parameters:** 0.5273%

## Files

- `LexAI_LoRA_Legal_Clause_Classification.ipynb` — Implementation notebook
- `DOCUMENTATION.md` — Detailed project documentation
- `confusion_matrix.png` — Evaluation result

## Key Learning

This task provided practical experience with **LLM fine-tuning, LoRA, dataset preparation, model evaluation, and domain-specific NLP**.

> This project is for academic and experimental purposes only and is not intended to provide legal advice.
