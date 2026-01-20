# LLaMA-3.2 Conversational Fine-Tuning

## Overview
This project focuses on fine-tuning a **LLaMA-3.2-3B** language model on **human–assistant conversations** to improve the quality and coherence of generated responses.

## Dataset
- ShareGPT-style conversational dataset    
- Reformatted using LLaMA chat templates  

## Methodology
- Supervised Fine-Tuning (SFT)
- Parameter-Efficient Fine-Tuning using **LoRA (PEFT)**
- Causal Language Modeling objective

## Evaluation
Model performance was evaluated using **ROUGE** metrics on a validation subset

## Technologies
Python, PyTorch, Hugging Face Transformers, TRL, Unsloth, LoRA, Hugging Face Datasets

## Results
The project demonstrates practical experience with large language model fine-tuning, conversational data processing, and quantitative evaluation of generative models.
