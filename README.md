# Character-Level Transformer (from scratch)

A character-level language model built from scratch, inspired by Andrej Karpathy’s “Neural Networks: Zero to Hero” playlist. The goal is to deepen my understanding of language models and deep-learning internals.

## Results
- **Parameters:** 6 298 972  
- **Dataset:** 6 M characters (90 % train / 10 % validation)  
- **Best metrics:** Validation loss **0.6895**, validation accuracy **78.52 %**

Loss curves for both training and validation are included directly in the repo root (see the PNG files).

## Tokenizer Experiments
I tested a custom tokenizer, but results didn’t improve, so the model remains character-level.

## Dataset
- **Source:** roneneldan/TinyStories (Hugging Face)
- **License:** CDLA-Sharing 1.0 (dataset only)
- **Note:** Raw dataset files are *not* committed to this repository

### Quick note
Training ran on Google Colab GPUs. The final code was copied into the notebook in this repo, so there may be minor path issues or typos.
