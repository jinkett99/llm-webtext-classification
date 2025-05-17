# Webtext Feature Extraction & Business Profiling with LLMs

## Overview
In this repository, we explore various advanced methodologies for optimal feature extraction from unstructured business webtext data. The objective is to enable effective business profiling—specifically, identifying the hiring status of firms—by leveraging:

- **LLM-based summarization** to distill relevant content from raw/unstructured and incoherent website text.
- **Finetuning BERT for Sequence Classification** to run training epoch and validate firm hiring status.
- **Parameter-Efficient Fine-Tuning (PEFT)** methods, focusing on **LoRA (Low-Rank Adaptation)** for efficient model adaptation.

These techniques aim to improve model interpretability, scalability, and performance across diverse web-based business text sources.

## Notebooks
```
notebooks/
├── webtext_summary.ipynb               # Summarizes business website content using LLM techniques
├── BertForSequenceClassification.ipynb # Fine-tunes a BERT encoder, performs hyperparameter tuning & evaluation
├── LoRA.ipynb                          # Exploratory notebook on Parameter-Efficient Fine-Tuning using LoRA
```

## Folder Structure
```
├── data/       # Relevant input datasets (not included in repo)
├── models/     # Stores fine-tuned BERT models (organized by version)
├── notebooks/  # Jupyter notebooks for experimentation and training
├── README.md   # Project documentation
```

## Goals
- Develop robust webtext summarization pipelines for language model input.
- Enable accurate classification of firm hiring status from summarized text.
- Compare summarized vs non-summarized text as inputs for BERTForSequenceClassification fine-tuning.
- Perform LM fine-tuning with hyperparameter tuning and evaluate metrics - With focus on F1-score and ROC-AUC.
- Experiment with PEFT techniques, LoRA in particular for fine-tuning optimization.

## Contributions
Feel free to open issues or submit pull requests for improvements or extensions.
