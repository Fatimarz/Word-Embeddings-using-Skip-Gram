
## Project Overview
This project creates word embeddings using the Skip-Gram model on mental health text data. The data is cleaned, preprocessed, and tokenized to generate training pairs for the embedding model. After training, the model outputs 100-dimensional vectors representing word semantics. The embeddings enable computation of word similarity via cosine similarity.

## Key Steps
- Loaded and cleaned mental health dataset from CSV.  
- Tokenized and generated Skip-Gram pairs for training.  
- Built and trained a neural embedding model with 100D vectors over 50 epochs.  
- Saved embeddings and implemented cosine similarity search for semantic analysis.

## Usage
- Load embeddings from file.  
- Query similar words using cosine similarity.
