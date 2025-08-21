# Harry Potter Character Similarity Analysis

This project analyzes character relationships in the Harry Potter series using Word2Vec embeddings trained on character dialogues.

## Overview

The analysis uses natural language processing techniques to:
1. Extract and preprocess dialogue from Harry Potter books
2. Train Word2Vec models on character speeches
3. Create character embeddings by averaging their dialogue vectors
4. Calculate cosine similarity between character embeddings
5. Identify character clusters and relationships


## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/character-similarity.git
cd character-similarity

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Notebook
jupyter notebook notebooks/character_similarity.ipynb

📊 Results

Word2Vec embeddings were trained on character dialogues.
Cosine similarity was used to find most similar characters.
The top character similarity pairs are visualized as a heatmap.

🛠 Dependencies

Python 3.8+
pandas
numpy
gensim
scikit-learn
matplotlib
seaborn

