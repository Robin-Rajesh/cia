# 📖 Short Story Generation with FLAN-T5

A notebook (CIA 1, Task 2) that uses Google's **FLAN-T5 Large** model to write short stories from one-line prompts.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-Transformers-FFD21E)

## 🧪 What it does

1. Loads `google/flan-t5-large` with Hugging Face Transformers.
2. Prompts it with *"Write a short story about: …"* for three titles:
   - *The Lost City of Code*
   - *A Journey Through the AI Forest*
   - *The Day Robots Took Over*
3. Generates up to 256 tokens per story using sampling, and prints each one.

## 🚀 Running

```bash
pip install transformers sentencepiece torch jupyter
jupyter notebook CIA_1_TASK_2.ipynb
```

The model (about 3 GB) downloads on first run.
