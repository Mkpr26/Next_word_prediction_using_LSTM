# Next Word Prediction using LSTM

A neural network model that predicts the next word given a sequence of words, trained on Shakespeare’s *Hamlet*. The project includes data preprocessing, model training (with and without early stopping), evaluation, and a deployed demo via Streamlit.

## 🧾 Table of Contents

- [Project Description](#project-description)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Setup & Installation](#setup--installation)  
- [Training & Experiments](#training--experiments)  
- [Demo / App](#demo--app)  
- [Files in Repository](#files-in-repository)  
- [Future Work](#future-work)  

## 🔍 Project Description

This project uses a dataset derived from *Hamlet* (shakespeare text) to build a **Next Word Prediction** model. The model takes as input a sequence of words and learns to predict what word comes next. An LSTM-based architecture is trained on the text, with experiments including early stopping to avoid overfitting. A Streamlit app is provided so users can interactively input text and get predictions for the next word.

Use this app for next word prediction :https://mkpr26-nextword-lstm.streamlit.app/

## ✅ Features

- Data preprocessing: tokenization, sequence generation, padding, vocabulary building  
- Two model versions: basic LSTM model and LSTM with early stopping  
- Saving tokenizer and model weights for reuse  
- Interactive web app for real-time next-word prediction  
- Hyperparameter experiments (sequence length, embedding size, number of LSTM units, etc.)  

## 🛠 Technologies Used

| Component | Details |
|---|---------|
| Programming Language | Python |
| Deep Learning Framework | TensorFlow / Keras (LSTM) |
| Data Handling & Preprocessing | Python built-ins, NumPy, tokenizer utilities |
| Model Persistence | Saved models (`next_word_lstm.h5`, early stopping version) and `tokenizer.pickle` |
| Deployment | Streamlit app (hosted at https://mkpr26-nextword-lstm.streamlit.app/) |
| Notebooks | `experiemnts.ipynb` for training / comparing models |
| Dataset | `hamlet.txt` (Shakespeare text) |
| Dependencies | Listed in `requirements.txt` |

## 🚀 Setup & Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/Mkpr26/Next_word_prediction_using_LSTM.git
   cd Next_word_prediction_using_LSTM
