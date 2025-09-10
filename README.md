# Movie Review Sentiment Analysis (RNN)

## 🎯 Objective

This project applies **Recurrent Neural Networks (RNNs)** to classify the sentiment of multilingual movie reviews.

Key features:
- Preprocessing of raw text (cleaning, tokenisation, encoding)
- Multiple architectures tested (SimpleRNN, Bi-RNN, LSTM, GRU)
- Data augmentation for balanced training
- Sentiment classification from continuous review scores
- Evaluation with accuracy, confusion matrices, and attention visualisation

---

## 📚 Background

Sentiment analysis helps businesses, researchers, and platforms interpret public opinion at scale.  
RNNs are suited for this task because they:
- Maintain context across sequences of words
- Work with variable-length text (short reviews to long paragraphs)
- Detect subtle cues of positive, negative, or neutral sentiment

This project shows how deep learning can uncover emotional signals in real-world, multilingual reviews.

---

## 📊 Dataset

The dataset contains **525 movie reviews** across multiple languages:

| Language | Count |
|----------|-------|
| English  | 297   |
| Malay    | 226   |
| Chinese  | 1     |
| Japanese | 1     |
| **Total** | **525** |

- Each entry includes a text review, a continuous sentiment score (0–1), and a language label.
- Lower scores indicate better ratings.
- Two rows with missing values were excluded.

---

## 🌍 Multilingual Approach

Instead of discarding non-English data, all reviews were retained. This improves:
- Dataset richness (important given the small sample size)
- Cross-linguistic model generalisation
- Realistic simulation of multilingual applications
