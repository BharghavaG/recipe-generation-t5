# 🍳 Recipe Generation using T5

This project fine-tunes the `t5-small` model to generate recipes from a list of ingredients.

## 📌 Features
- Fine-tuning `t5-small` for recipe generation
- Uses a dataset of **200,000** recipes
- Supports inference for generating new recipes
- Evaluation using `BLEU`, `ROUGE`, and `METEOR` scores

## 📂 Project Structure
- `data/` - Dataset files
- `models/` - Saved fine-tuned models
- `scripts/` - Training, evaluation, and inference scripts
- `notebooks/` - Jupyter notebooks for experimentation

## 🛠 Installation
```bash
git clone https://github.com/YOUR_USERNAME/recipe-generation-t5.git
cd recipe-generation-t5
pip install -r requirements.txt
