# Language-Detection-using-LSTM

Overview
Language detection is crucial for many Natural Language Processing (NLP) tasks, including translation, text processing, and sentiment analysis. In this project, we leverage LSTM networks, which are known for their ability to capture long-term dependencies in sequential data, to build a robust language detection system.

Features
Dataset: Text data containing labeled language categories.
Model Architecture: LSTM-based model for sequence classification.
Preprocessing: Text tokenization, padding, and one-hot encoding for input sequences.
Training: Model trained on language-labeled text data.
Evaluation: Performance evaluated using accuracy and other relevant metrics.
Requirements
Python 3.10+
Keras 2.x
TensorFlow 2.x
Numpy 1.26.4
Pandas 2.2.2
Scikit-learn


#Model Details
Embedding Layer: Converts the tokenized words into dense vectors.
LSTM Layer: Captures sequential patterns in the text data.
Dense Output Layer: Provides the predicted language category using softmax activation.


x_train: Tokenized text data.
y_train: Language labels encoded using one-hot encoding.
