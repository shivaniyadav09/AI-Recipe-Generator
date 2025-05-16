# 🍲 AI-Powered Recipe Generator using Gemini API

This project enhances raw recipe data using **Google's Gemini 2.0 Flash model**, generating human-friendly, detailed cooking instructions with ingredients, tips, and customization options.

## 📌 Project Highlights

- Uses **Kaggle’s Food.com Recipes Dataset** with 180K+ entries
- Cleans and extracts relevant recipe fields using Python
- Leverages **Gemini API** for content generation
- Generates structured, enhanced recipes from raw inputs
- Supports querying by food name (e.g., "Cabbage Soup")

---

## 🧠 Tech Stack

- **Python 3.10+**
- **pandas** – DataFrame manipulation
- **csv** – Raw CSV cleaning
- **google.generativeai** – Gemini 2.0 Flash model for text generation
- **Jupyter / Colab** – Development & execution environment

---

## 📂 Dataset Source

- **Kaggle:** [Food.com Recipes and Reviews](https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews)
- Contains recipes with ingredients, instructions, cook times, and user reviews.

---

## 🔧 How It Works

1. Load and clean the Kaggle CSV data
2. Extract key fields: `Name`, `Description`, `TotalTime`, `RecipeInstructions`
3. User inputs a recipe name
4. Structured prompt sent to Gemini API
5. Enhanced recipe with:
   - Ingredients
   - Cooking steps
   - Tips & variations
   - Serving suggestions

---
