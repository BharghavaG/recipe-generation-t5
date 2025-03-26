# Recipe Generation using T5

This project focuses on fine-tuning the T5-small model to generate recipes based on a given list of ingredients. The goal is to create an AI-powered recipe generator that suggests complete recipes, including the title, ingredients, and step-by-step cooking directions.

Instead of relying on predefined recipe databases, the model learns patterns from a dataset of recipes and generates new ones dynamically. This approach allows users to get customized recipes based on available ingredients at home.

---

## Features
- Fine-tuning `t5-small` for recipe generation
- Uses a dataset of **20,000** recipes
- Supports inference for generating new recipes
- Evaluation using `BLEU`, `ROUGE`, and `METEOR` scores

---

## Project Structure
- `reduced_recipe.csv` - Dataset file
- `recipe_gen.ipynb` - Jupyter notebook

---

## Tech Stack
- Model: t5-small (Hugging Face Transformers)
- Dataset: Recipe dataset (title, ingredients, directions)
- Framework: PyTorch & Hugging Face Transformers
- Training: Trainer API for efficient fine-tuning
- Optimization: Mixed precision (FP16) for faster training

---

## Installation and Setup

1. Clone the repository:
   ```bash
   https://github.com/BharghavaG/recipe-generation-t5.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any questions or suggestions, please open an issue or contact us at goudibharghava@gmail.com.
