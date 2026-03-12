## Project Overview

This repository contains a beginner-friendly implementation of a GPT-style language model built completely from scratch in PyTorch. The project follows a two-stage pipeline:

1. **Pretraining** on raw text from TinyStories using next-token prediction.
2. **Supervised fine-tuning (SFT)** on instruction-response examples to improve instruction following.
#link foi collab:
[collab](https://colab.research.google.com/drive/1tG05xwRVpNH6dS-p9cgajFxEKxqo1hA3?usp=sharing)

https://colab.research.google.com/drive/1tG05xwRVpNH6dS-p9cgajFxEKxqo1hA3?usp=sharing
## Features

- Decoder-only transformer architecture
- Byte-Pair Encoding (BPE) tokenizer
- Pretraining on raw text
- Fine-tuning on instruction-format data
- Text generation before and after fine-tuning
- Evaluation using loss curves and perplexity

## Tech Stack

- Python
- PyTorch
- Hugging Face Datasets
- Tokenizers
- Google Colab
