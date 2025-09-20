# Exploring Language Modeling with N-Gram Sizes and Smoothing Techniques

This project explores classical **n-gram language models** and compares different **smoothing techniques** to handle sparsity in natural language. Using the IMDB Reviews dataset, models are evaluated with **perplexity** and analyzed with visualizations.

---

## ⚙️ Features
- Preprocessing text (lowercasing, tokenization, cleaning).
- Implementing **unigram and bigram models**.
- Applying smoothing techniques:
  - Laplace (Add-One) Smoothing
  - Good-Turing Discounting
  - Kneser-Ney Smoothing
- Calculating **probabilities & perplexity**.
- **Cross-validation** for robust evaluation.
- Visualization of results (bar and line charts).

---

## 📊 Results
- **Unigram + Good-Turing**: Best perplexity (≈1159).  
- **Bigram + Kneser-Ney**: Balanced performance (≈1379), captures context better than unigrams.  
- **Laplace & Good-Turing for bigrams**: Struggled due to data sparsity (very high perplexity).

 ---

## 📂 Dataset
- **IMDB Reviews Dataset**  
  Download from Kaggle: [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

