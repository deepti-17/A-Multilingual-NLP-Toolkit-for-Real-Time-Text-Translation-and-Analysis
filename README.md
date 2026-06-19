# 🌍 Multilingual NLP Pipeline for News Analysis

An end-to-end Natural Language Processing (NLP) pipeline that performs **machine translation, text summarization, sentiment analysis, and named entity recognition (NER)** on multilingual news articles using state-of-the-art Transformer models from Hugging Face.

The project demonstrates how multiple pretrained NLP models can be integrated into a unified workflow for automated multilingual text analysis.

---

## Features

- 🌐 Machine Translation across multiple Indian languages
- 🔄 Back Translation for translation quality verification
- 📝 Abstractive Text Summarization
- 😊 Sentiment Analysis
- 🏷️ Named Entity Recognition (NER)
- 💬 Interactive text inference on custom user inputs
- 📊 End-to-end multilingual news analysis pipeline

---

## Dataset

- **4,500+ multilingual news articles**
- Articles available in multiple Indian languages
- Used for evaluating translation and downstream NLP tasks

---

## Models Used

| Task | Model |
|------|-------|
| Machine Translation | mBART |
| Back Translation | mBART |
| Text Summarization | BART |
| Sentiment Analysis | Multilingual BERT |
| Named Entity Recognition | Multilingual BERT |

All models were loaded using the **Hugging Face Transformers** library.

---

## Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- BERT
- mBART
- BART
- NumPy
- pandas
- Matplotlib

---

## Project Workflow

```
Input News Article
        │
        ▼
Machine Translation
        │
        ▼
Back Translation
        │
        ▼
Text Summarization
        │
        ▼
Sentiment Analysis
        │
        ▼
Named Entity Recognition
        │
        ▼
Structured Output
```

The pipeline performs:

- Translation
- Back Translation
- Summarization
- Sentiment Classification
- Named Entity Recognition

and returns the processed output.

---

## Sample Tasks

✔ English → Hindi Translation

✔ Hindi → English Translation

✔ News Summarization

✔ Entity Extraction

✔ Sentiment Prediction

---

## Key Learnings

- Working with Transformer-based NLP models
- Multilingual language processing
- Hugging Face model integration
- Sequence-to-sequence generation
- Text classification
- Named entity recognition
- End-to-end NLP pipeline design

---

## Future Improvements

- Fine-tune models on domain-specific datasets
- Deploy the pipeline using Flask or FastAPI
- Add BLEU and ROUGE evaluation metrics
- Support additional languages
- Build a web-based interface

---
