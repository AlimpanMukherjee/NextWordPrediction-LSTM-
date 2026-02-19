Next Word Prediction using LSTM
Overview-Built an LSTM-based language model trained on Shakespeare’s Hamlet to predict the next word in a given sequence.

Model Architecture
-------------------
Embedding → LSTM → Dense (Softmax)

Workflow
---------
Text preprocessing and tokenization  --->  Sequence generation and padding  --->  Model training for next-word prediction  --->  Inference for text generation


Tech Stack
-----------
Python, TensorFlow/Keras, NumPy

Future Work
------------
Temperature sampling , Larger dataset training
