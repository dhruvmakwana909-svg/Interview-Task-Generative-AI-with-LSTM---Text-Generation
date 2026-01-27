LSTM Text Generation using Shakespeare Dataset

--> Project Overview

This project implements a Generative AI text generation model using Long Short-Term Memory (LSTM) networks.
The model is trained on Shakespeare’s Complete Works to learn linguistic patterns and generate coherent text based on a given seed input.

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

--> Dataset Used: Shakespeare’s Complete Works

--> Technologies Used

Python

TensorFlow / Keras

NumPy

--> Key Learnings

LSTMs are effective for modeling long-term dependencies in text

Word-level tokenization captures semantic meaning better than character-level

Deeper LSTM layers improve contextual understanding

Early stopping improves generalization

--> Bonus Experiments

Increased LSTM depth → improved grammatical flow

Larger sequence length → better context retention

Tested different embedding sizes

--> Training VS Validation Loss Graph
<img width="640" height="480" alt="Loss" src="https://github.com/user-attachments/assets/bc5573b4-db7c-4a39-b25c-03812a3468dd" />


--> Training VS Validation Accuracy Graph
<img width="640" height="480" alt="Accuracy" src="https://github.com/user-attachments/assets/f6aed986-ea16-4611-8787-bccfc2c2a3ec" />

