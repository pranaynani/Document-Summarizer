# 🧠 NLP Final Project - Text Summarization using Transformers

## 📌 Project Overview

This project focuses on the development and evaluation of an **abstractive text summarization** system using transformer-based models. The goal is to generate concise summaries of long documents while retaining key information and maintaining natural language fluency.

We experiment with:
- Pretrained transformer models (e.g., **BART**, **T5**)
- Fine-tuning on a summarization dataset
- Evaluation using standard metrics like **ROUGE**

---

## 📚 Dataset

We utilize the **XSum dataset**:
- Single-document, single-sentence summarization
- Contains news articles and corresponding human-written summaries
- Source: [Hugging Face Datasets - XSum](https://huggingface.co/datasets/xsum)

---

## 🚀 Models Used

- `facebook/bart-large-cnn`
- `t5-small`

Both models are evaluated on their ability to generate fluent and accurate summaries after fine-tuning.

---

## 🛠️ Key Features

- Data preprocessing (tokenization, truncation, padding)
- Model training and evaluation
- ROUGE-based performance analysis
- Human evaluation of model summaries
- Inference examples with comparison of different models

---

## 📊 Evaluation Metrics

We use the following metrics for evaluation:
- **ROUGE-1** (unigram overlap)
- **ROUGE-2** (bigram overlap)
- **ROUGE-L** (longest common subsequence)

These help quantify the quality of generated summaries against reference summaries.

---

## 🧪 Results

| Model             | ROUGE-1 | ROUGE-2 | ROUGE-L |
|------------------|---------|---------|---------|
| BART (fine-tuned)| 38.1    | 17.5    | 35.4    |
| T5 (fine-tuned)  | 32.9    | 12.3    | 24.2    |


---

