# Sentiment Analysis Using RNN, LSTM, and GRU Models

This project compares the performance of **RNN**, **LSTM**, and **GRU** models for sentiment analysis. The goal is to classify text into **positive**, **negative**, or **neutral** sentiments. The project also explores the impact of hyperparameter tuning on model performance.

---

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/Elizabeth-Mwania/sentiment-analysis-with-RNNS-LSTM-GRU.git

2. Set up a virtual environment and install dependencies
    numpy==1.21.0
    pandas==1.3.0
    tensorflow==2.6.0
    keras-tuner==1.0.3
    scikit-learn==0.24.2
    matplotlib==3.4.2
    nltk==3.6.2
3. Dataset generation
    The dataset is custom-generated using the ollama library.
    Contains 1,458 samples labeled as positive, negative, or neutral.
   
    Preprocessing includes:
    Removal of punctuation and stopwords.
    Tokenization and padding of sequences.
    One-hot encoding of sentiment label
 5. Word Embeddings using Word2Vec
 6. Hyperparameter tuning using Keras tuner
 7. Metrics: Accuracy, Precision, Recall, F1-score
 8. Testing 
