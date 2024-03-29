
# Trainging Llama2 with Thai language

## Overview

This project focuses on training a Llama2 style model from scratch on the "prachathai67k" dataset for an NLP task involving the Thai language. 

## Preprocessing and Tokenization

- Utilizes `AutoTokenizer` from "pythainlp/thainer-corpus-v2-base-model".
- Custom preprocessing aligns input and label sequences for model training.

## Model Training

- Architecture: Custom Transformer model defined in `model.py`, inspired by Llama2, with specific dimensions and layers tailored for the task.
- Training involves careful optimization, including loss calculation adjustments and performance evaluation over epochs.

## Results

The current results indicate that the model has not yet been optimized and continues to overfit the training data. This suggests there is room for improvement by fine-tuning hyperparameters to achieve a better balance between the model's performance on the training data and its generalization to unseen data.
