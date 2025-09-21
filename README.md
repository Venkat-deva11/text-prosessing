# Text Preprocessing and Bag-of-Words Feature Extraction

This repository demonstrates a simple **Natural Language Processing (NLP)** pipeline:
1. Load raw text data.
2. Preprocess text (cleaning, lowercasing, stopword removal, stemming).
3. Convert preprocessed text into numerical features using **Bag-of-Words**.

## 📂 Dataset
- Input: `sampleDataste.txt`  
- Format: Tab-separated file with two columns:
  - `labels` → Category of the message (e.g., spam/ham).
  - `messages` → Raw text message.

Example:
ham Hello, how are you?
spam Win $$$ now!!!
