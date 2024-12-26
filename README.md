# Finetuning_LLMs

This repository covers three key components for improving the model's performance and query-handling capabilities:
1. **Fine-tuning Gemma with QLoRA**
2. **Loading and Preparing Dataset for Fine-tuning**
3. **Integrating ChromaDB for Enhanced Query Handling**


## Project 1: Fintuning_LLAMA2

This file contains code and resources for training a fine-tuned LLaMA-based language model using **LoRA** (Low-Rank Adaptation) techniques. The project utilizes the Hugging Face Transformers and Accelerate libraries, in addition to PEFT (Parameter-Efficient Fine-Tuning) to efficiently train and fine-tune large language models with low memory usage and computational costs.


## Project 2: Gemma_finetuning with QLoRA

This file focuses on fine-tuning the **Gemma model** using **QLoRA** (Quantized Low-Rank Adaptation) to optimize memory usage during training. Gemma is a large language model (LLM) used for tasks such as code generation. The goal of this project is to fine-tune the model for specific tasks, such as generating code from natural language instructions, while ensuring efficient use of computational resources by employing quantization techniques.

## Project 3: finetune_gemma+chromadb

This file presents a comprehensive solution for fine-tuning large language models, preparing a dataset for code generation tasks, and integrating **ChromaDB** to enhance query handling. By combining these approaches, the repository provides a robust framework for improving the performance and efficiency of large models when used for real-time tasks like code generation and structured query answering.

