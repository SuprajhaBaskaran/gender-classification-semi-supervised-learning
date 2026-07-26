# Gender Classification via Semi-Supervised Learning

This project explores semi-supervised learning for speech-based gender classification. It combines handcrafted MFCC features and Wav2Vec2 embeddings with pseudo-labeling to improve classification performance when labeled data is limited.

## Dataset

The dataset used in this project is the **Malayalam Multispeaker Speech Dataset**, available on Kaggle:

https://www.kaggle.com/datasets/kurianbenoy/malayalam-multispeaker-speech-data-set

## Features

- MFCC feature extraction
- Wav2Vec2 embeddings
- Semi-supervised learning with pseudo-labeling
- Logistic Regression classifier
- Performance evaluation using Accuracy, F1-score, and ROC-AUC

## Technologies

- Python
- PyTorch
- Librosa
- Hugging Face Transformers
- Scikit-learn
- NumPy
- Pandas
