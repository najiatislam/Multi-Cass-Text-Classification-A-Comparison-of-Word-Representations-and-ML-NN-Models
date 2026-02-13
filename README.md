# Multi-Class Text Classification: Word Representations & Model Comparison
Comparing TF-IDF + classical ML vs Word2Vec + deep learning models (RNN, LSTM, GRU, BiLSTM) on news headline classification.

## Key Highlights
- Dataset: ~93k train / 60k test samples
- Baselines: Random Forest + TF-IDF
- Best performer: BiLSTM with Word2Vec embeddings
- Full pipeline: preprocessing, EDA, model training, evaluation, discussion

## Results
BiLSTM achieved highest accuracy, demonstrating superiority of sequential models over bag-of-words approaches.


Built with Python, scikit-learn, PyTorch, Gensim.
