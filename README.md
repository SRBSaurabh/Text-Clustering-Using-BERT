# Text Clustering and Topic Modeling of All ArXiv Articles

This repository provides a modularized implementation of BERTopic for topic modeling using sentence embeddings. The script loads an NLP dataset, generates embeddings, and trains a BERTopic model.

## What This Project Does
- Loads an NLP dataset from Hugging Face
- Generates sentence embeddings using Sentence Transformers
- Trains a BERTopic model for topic modeling
- Saves the trained model for later use

## Installation

```bash
pip install bertopic datasets sentence-transformers
```

## Usage

Run the main script to train a topic model:

```bash
python main.py
```

The trained model will be saved as `bertopic_model`.

## Files
- `main.py` - The main script to run the pipeline
- `README.md` - Documentation for setup and usage

## Requirements
- Python 3.7+
- BERTopic
- Hugging Face Datasets
- Sentence Transformers

## License
This project is licensed under the MIT License.

