# HW_MDDM-Text-classification-with-Maximum-Entropy-Model

# Sarcasm Detection using Maximum Entropy (MaxEnt) Model

This repository contains a Jupyter Notebook to classify news headlines as sarcastic or not using a Maximum Entropy model.

## 📂 Files

- `homework_start-2.ipynb`: Main notebook for the assignment.
- `data/train_data.json`: Training data (must be downloaded).
- `data/tests_data.json`: Test data (must be downloaded).

## 📊 Dataset

The dataset comes from a Kaggle competition and includes:
- Headlines from The Onion (sarcastic)
- Headlines from HuffPost (non-sarcastic)

Each entry includes:
- `headline`: News title
- `is_sarcastic`: 1 for sarcastic, 0 for not
- `article_link`: (ignored)

## 🔧 Requirements

```bash
pip install numpy pandas matplotlib scikit-learn
