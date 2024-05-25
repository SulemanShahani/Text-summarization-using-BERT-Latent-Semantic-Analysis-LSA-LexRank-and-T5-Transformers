# Text summarization using BERT,Latent Semantic Analysis LSA,LexRank and T5 Transformers

## Overview

This repository provides implementations of various text summarization techniques using Python libraries like Transformers, PyMuPDF, and sumy. The techniques covered include BART, T5, LSA, and LexRank. 

## Prerequisites

Make sure you have the following installed:
- transformers
- PyMuPDF
- sumy
- nltk

You can install them using pip:

```bash
pip install transformers PyMuPDF sumy

import nltk
nltk.download('punkt')


# Make sure to replace '/content/eng.pdf' with your file path

## Summarization Techniques

### 1. LexRank

- **Description**: 
  - Selects sentences with the highest centrality scores.
  - Importance determined by similarity to other sentences.
- **Implementation**: 
  - Based on graph-based methods.
- **Use Cases**:
  - Effective for summarizing lengthy documents with multiple themes.

### 2. Latent Semantic Analysis (LSA)

- **Description**: 
  - Identifies significant sentences by their contribution to latent topics.
  - Sentences with high weights on important topics are selected.
- **Implementation**: 
  - Utilizes linear algebra techniques.
- **Use Cases**:
  - Suitable for summarizing documents with complex semantic structures.

### 3. BERT and T5

- **Description**: 
  - Transformer-based models pre-trained on large text corpora.
  - Capable of both extractive and abstractive summarization.
- **Implementation**: 
  - Utilizes deep learning techniques.
- **Use Cases**:
  - Ideal for generating high-quality summaries for various types of documents.

## Comparison

- **LexRank, LSA, and TextRank**:
  - Traditional algorithms based on graph and linear algebra.
- **BERT and T5**:
  - State-of-the-art transformers using deep learning.
- **Choosing the Right Technique**:
  - Depends on factors like text size, nature, desired summary type, and computational resources.


