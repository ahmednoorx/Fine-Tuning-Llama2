# Fine-Tuning Llama2

## Overview
This project demonstrates how to fine-tune the Llama2 language model using the Hugging Face ecosystem and test the resulting model.

## Contents
- `Fine_tune_Llama_2.ipynb`: Notebook for fine-tuning Llama2 using QLoRA and PEFT.
- `Fine_Tune_Model_Test.ipynb`: Notebook for loading and testing the fine-tuned model.

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ahmednoorx/Fine-Tuning-Llama2.git
   cd Fine-Tuning-Llama2
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **(Optional) Set up Hugging Face authentication:**
   - If pushing to the Hugging Face Hub, run in a notebook cell:
     ```python
     !huggingface-cli login
     ```

## Usage

- Run `Fine_tune_Llama_2.ipynb` to fine-tune the model.
- Run `Fine_Tune_Model_Test.ipynb` to test the fine-tuned model.

## Notes

- You may need a GPU with sufficient VRAM for training.
- The `.env` file (if used for tokens) is ignored by git.

## Acknowledgments

Based on a YouTube tutorial, with enhancements and documentation by me.