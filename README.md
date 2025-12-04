# TextPredictor
This project builds a Next Word Prediction model using Deep Learning (LSTM) and Natural Language Processing (NLP) techniques. The model is trained on a sample dataset of wiki text and learns patterns in language to predict the most likely next word in a sentence.

🚀 Project Overview

The goal of this project is to generate text intelligently by predicting the next word based on previous words, similar to typing suggestions on keyboards or chat applications.

Key steps in the project:

Load and clean raw text data

Tokenize text and create word sequences

Convert sequences into training data (input & labels)

Train an LSTM-based neural network

Predict the next word for a given input phrase


🏗 Technologies Used
Technology	Purpose
Python	Main programming language
TensorFlow / Keras	Model building & training
LSTM Neural Network	Sequence learning
Tokenizer & Pad Sequences	Text preprocessing
📦 Dataset

A Wikipedia dataset was used to train the model. Only 3000 cleaned lines of text were used to reduce processing time.

🔧 Model Architecture

Embedding Layer – converts words into vector representations

LSTM Layer – learns long-term language patterns

Dense Layer (Softmax) – outputs probability of each word

🧪 Example Usage
sentence = "life is"
print(predict_next(sentence))


Output example:

life is beautiful

🎯 Results

The model successfully predicts meaningful next words based on context and improves with more training data and epochs.

📌 Future Improvements

Predict multiple next words

Add beam search for better sentence generation

Create a web or GUI interface

Train on a larger dataset for increased accuracy

