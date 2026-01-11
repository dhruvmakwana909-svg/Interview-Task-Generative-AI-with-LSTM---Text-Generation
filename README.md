LSTM Text Generation using Shakespeare Dataset

--> Project Overview

This project implements a Generative AI text generation model using Long Short-Term Memory (LSTM) networks.
The model is trained on Shakespeare’s Complete Works (public domain) to learn linguistic patterns and generate coherent text based on a given seed input.

The project covers the entire NLP pipeline:

Text preprocessing

Tokenization & sequence generation

LSTM model design

Model training with early stopping

Text generation from seed phrases

--> Features

Word-level text generation

Multi-layer LSTM architecture

Early stopping to prevent overfitting

Custom seed-based text generation

Clean and well-documented code

--> Model Architecture

Embedding Layer → LSTM (150 units) → LSTM (100 units) → Dense (Softmax)

Embedding Dimension: 100

Loss Function: Categorical Crossentropy

Optimizer: Adam
