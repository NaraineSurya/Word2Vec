# Word2Vec Implementation with Reddit News and Google News Datasets

## Overview

This project implements Word2Vec models using two different datasets: the Reddit News Dataset and the pre-trained Google News Dataset. The Word2Vec model is used to generate word embeddings that capture semantic relationships between words. The embeddings can be used for various natural language processing (NLP) tasks such as text classification, clustering, and similarity analysis.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Datasets](#datasets)
- [Installation](#installation)

## Prerequisites

- Python 3.6 or later
- Jupyter Notebook (optional, for interactive development)
- The following Python libraries:
  - `gensim`
  - `numpy`
  - `pandas`
  - `nltk`

## Datasets

### Reddit News Dataset

The Reddit News Dataset consists of headlines from the Reddit WorldNews channel. The dataset can be downloaded from [Kaggle](https://www.kaggle.com/aitzhan7/reddit-news).

### Google News Dataset

The Google News Dataset includes a pre-trained Word2Vec model trained on a large Google News corpus. The pre-trained model can be downloaded from [Google Code Archive](https://code.google.com/archive/p/word2vec/).

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/word2vec-reddit-google-news.git
cd word2vec-reddit-google-news
```

2. Install Dependencies:
   
```bash
pip install gensim
pip install pandas
pip install nltk
```
