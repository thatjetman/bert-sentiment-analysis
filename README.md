# bert-sentiment-analysis
Jupyter Notebook for BERT sentiment analysis, accompanying my Medium blog
# BERT Sentiment Analysis

This Jupyter Notebook demonstrates sentiment analysis using BERT to classify movie reviews as positive or negative. It accompanies my [Medium blog](#)  and aligns with the SST-2 task (94.9% accuracy). The code uses Hugging Face’s `transformers` library and shows BERT’s input representation (`[CLS]`, `[SEP]`).

## Overview
- **Purpose**: Classify reviews (e.g., “This movie was fantastic!” → Positive).
- **Model**: `bert-base-uncased`.
- **Features**: Displays tokens, segment IDs, and attention mask.

## Prerequisites
- Python 3.7+
- Install dependencies:
  ```bash
  pip install -r requirements.txt
