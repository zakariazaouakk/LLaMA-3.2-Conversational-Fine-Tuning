LLaMA-3.2 Conversational Fine-Tuning
Overview

Fine-tuning a LLaMA-3.2-3B model on 100k human–assistant conversations using LoRA (PEFT) to improve conversational response quality.

Dataset

100k ShareGPT-style human conversations

Multi-turn dialogue format

Converted to LLaMA chat templates

Approach

Supervised Fine-Tuning (SFT)

Causal language modeling

LoRA-based parameter-efficient adaptation

Evaluation

ROUGE scores on a validation subset:

ROUGE-1: ~83%

ROUGE-2: ~81%

ROUGE-L: ~83%

Stack

Python · PyTorch · Transformers · TRL · Unsloth · LoRA · Hugging Face Datasets

Outcome

Demonstrates practical LLM fine-tuning, dialogue modeling, and quantitative evaluation.
