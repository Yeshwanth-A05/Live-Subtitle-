📘 A Comparative Analysis of Deep Learning Techniques for English–Tamil Text Translation
📌 Overview

This project presents a comparative study of deep learning models for English–Tamil Neural Machine Translation (NMT). The goal is to improve translation accuracy for the low-resource English–Tamil language pair using modern deep learning techniques such as Seq2Seq with Attention and Transformer architectures.

The project focuses on improving translation quality for applications in education, government, and healthcare domains.

🎯 Objectives

Study various deep learning models for English–Tamil translation

Compare performance of Seq2Seq and Transformer-based models

Implement attention mechanisms for better alignment

Improve translation quality using subword tokenization

Evaluate models using BLEU and chrF scores

❗ Problem Statement

Despite advancements in Neural Machine Translation, English–Tamil translation remains challenging due to:

Structural and grammatical differences

Rich morphology of Tamil

Limited parallel corpora

Vocabulary sparsity and rare word problems

Inaccurate translations affect usability in real-world domains such as education and healthcare.

🧠 Techniques Used

🔹 Sequence-to-Sequence (Seq2Seq) Architecture

🔹 Attention Mechanism

🔹 Transformer Architecture (Self-Attention)

🔹 Subword Tokenization (to handle rare words)

🔹 Word Embeddings

🏗️ Project Architecture

Workflow:

Data Acquisition
        ↓
Data Preprocessing (Cleaning, Tokenization, Padding)
        ↓
Train-Test Split
        ↓
Model Training (Transformer / Seq2Seq + Attention)
        ↓
Evaluation (BLEU, chrF)
        ↓
Inference (Tamil Translation Output)

🧩 Modules

Data Preparation Module

Text cleaning

Normalization

Subword segmentation

Text Representation Module

Tokenization

Embedding generation

Model Training Module

Transformer-based encoder-decoder

Attention mechanism

Performance Evaluation Module

BLEU Score

chrF Score

Translation Inference Module

Generate Tamil translations

Output Refinement Module

Detokenization

Final formatting

📊 Evaluation Metrics

Sentence-level BLEU

Corpus-level BLEU

chrF score

These metrics measure translation quality and alignment accuracy.

💻 Software Requirements

Python 3.8+

PyTorch 1.9+ / TensorFlow 2.x

Transformers Library

NumPy

Pandas

Scikit-learn

Matplotlib

NLTK / spaCy

🖥️ Hardware Requirements

GPU (NVIDIA GTX or better, 8GB+ VRAM recommended)

16GB RAM

Intel i7 / AMD Ryzen 7 (8+ cores)

SSD storage

📚 Literature Reference

Key foundational works include:

Bahdanau et al. (2014) – Attention Mechanism

Sutskever et al. (2014) – Seq2Seq with LSTM

Vaswani et al. (2017) – Transformer Architecture

Conneau & Lample (2019) – Pre-training for NMT

Tamil-English low-resource NMT studies (2020+)

🌍 Social Impact

This project supports:

SDG 4 – Quality Education

SDG 10 – Reduced Inequalities

It promotes language accessibility and digital inclusion for Tamil-speaking communities.

🚀 Future Improvements

Fine-tuning multilingual pretrained models (IndicBERT, mBART)

Increasing dataset size

Synthetic data generation

Domain-specific adaptation (medical/legal translation)

Low-resource transfer learning

👥 Team Members

Saliniyan P – 22ALR083

Sanjay A – 22ALR084

Yeshwanth A – 22ALR115

Project Guide:
Dr. K. Logeswaran
