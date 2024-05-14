# Enhanced Summarization of Conversational Texts with LLaMA and LoRA

This project aims to improve the summarization accuracy of customer and agent conversations by 40% through fine-tuning a pre-trained LLaMA model using the LoRA (Low-Rank Adaptation) framework. The repository contains a Jupyter notebook that outlines the step-by-step process to accomplish this enhancement.

## Project Objectives

- **Enhanced Summarization Accuracy**: Achieve a 40% improvement in summarization accuracy for conversational texts between customers and agents.
- **Utilization of LoRA Framework**: Implement the LoRA framework to fine-tune a large pre-trained language model, increasing its efficacy in processing and summarizing complex conversations.

## Installation

To set up your environment for running the notebook, install the required libraries using the following commands:

```bash
pip install torch==2.0.1 transformers==4.32.1 datasets==2.14.4 peft==0.5.0 bitsandbytes==0.41.1 trl==0.7.1 accelerate
