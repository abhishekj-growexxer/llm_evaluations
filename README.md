# LLM Evaluation HTML Table Generator

## Overview
This Python script generates an HTML table for evaluating multiple models using their corresponding `.npy` files as input. It's particularly useful for comparing the performance of different models in a tabular format.

## Features
- Accepts multiple `.npy` files as input.
- Generates an HTML table with evaluation metrics for each model.
- Provides a comprehensive overview of model performance.

## Usage
1. **Input Files**: Place all the `.npy` files you want to evaluate in the same directory as the script.
2. **Run Script**: Execute the Jupyter notebook.
3. **Output**: The script will generate an HTML file named `evaluation_table.html` containing the evaluation table.

## Evaluation files for these models are present:
- `LLaMA_pred.npy`
- `alpaca-lora-7b_pred.npy`
- `correct_answers_openai_embedd.npy`
- `flan_t5_answers_openai_embedd.npy`
- `flan_t5_pred.npy`
- `gpt_3_5_turbo_pred.npy`
- `llama2-13b.npy`
- `new_alpaca-lora-7b-hf.npy`
- `open-llama-3b.npy`
- `openchat_v2_pred_41.npy`
- `openchat_v2_pred_75.npy`
- `vicuna-13b-hf-2.npy`

Running the script will generate an HTML table summarizing the evaluation metrics for each model.

## Requirements
- Python 3.8 +
- NumPy
- (Optional) Jupyter Notebook for easier visualization and customization
