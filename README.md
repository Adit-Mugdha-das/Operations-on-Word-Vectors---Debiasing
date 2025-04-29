# Operations on Word Vectors - Debiasing

This repository contains the programming assignment from **Week 2** of **Course 5: Sequence Models** in the [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) by Andrew Ng on Coursera.

## Overview

In this assignment, various operations are performed on pre-trained GloVe word vectors to explore the semantic structure of word embeddings and address the issue of bias in language models.

You will implement:
- Vector arithmetic for analogy tasks (e.g., "king" - "man" + "woman" ≈ "queen")
- Cosine similarity to measure semantic similarity between words
- Bias direction detection (e.g., gender bias)
- Neutralization and equalization algorithms to debias word embeddings

This assignment demonstrates the importance of fairness and ethical considerations in AI systems that use language data.

## Contents

- `cosine_similarity()` – Computes similarity between word vectors
- `complete_analogy()` – Solves word analogy problems using vector arithmetic
- `neutralize()` – Removes bias direction from neutral words
- `equalize()` – Makes gender-paired words equidistant from the bias direction
- Jupyter Notebook – Walkthrough and explanations of each function
- `glove.6B.50d.txt` – Pre-trained 50-dimensional GloVe word vectors

## Technologies Used

- Python 3
- NumPy
- Pre-trained GloVe embeddings (Stanford NLP)

## Course Information

- Course: Sequence Models (Course 5 of 5)
- Specialization: Deep Learning Specialization
- Instructor: Andrew Ng
- Platform: Coursera
- Institution: DeepLearning.AI

## License

This repository is based on educational content provided by DeepLearning.AI through Coursera. It is intended for personal and academic use only. Redistribution for commercial purposes is not allowed.

---
