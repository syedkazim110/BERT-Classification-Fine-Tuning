# IMDB Sentiment Classification with BERT

This project fine-tunes a BERT-based model for binary sentiment classification (positive/negative) on the [IMDB movie reviews dataset](https://huggingface.co/datasets/imdb) using Hugging Face's `transformers` library.

---

## Project Structure

- **dataset** → IMDB dataset loaded via Hugging Face `datasets`
- **tokenizer** → `BertTokenizer` for preprocessing text
- **model** → `BertForSequenceClassification` fine-tuned for binary classification
- **trainer** → Hugging Face `Trainer` API for training and evaluation
